#Google Shopping (Ruby)

##Now with 100% more ruby and 100% less JavaScript

You've already done it in JavaScript... now lets try it again in Ruby. This will help you get ready to dive into Ruby and should teach you how to be resourceful.

Google has all of the answers. Start slow and use smart searching for things like...

* filtering an array in ruby
* mapping an array in ruby
* iterating over a hash in ruby
* etc...

##Getting Started

* Fork and clone this repo
* In the directory, type `gem install json` (`gem` is like npm for ruby)
* Type `ruby google_shopping.rb`
* open the file `subl google_shopping.rb` 
* Finish the problems below
* ???
* Profit

##Assignment (Déjà vu)
Use the product search result in your file to check the following:

1.) The `kind` of results you're are dealing are `shopping#products`. Go through the `items` and find all results that have `kind` of `shopping#product`. How many are there? Where else is this count information stored in the search results?

2.) Find all items with a `backorder` availability in `inventories`.

3.) Find all items with more than one image link.

4.) Find all `canon` products in the items (careful with case sensitivity).

5.) Find all `items` that have **product** **author** **name** of "eBay" and are brand "Canon".

6.) Print all the products with their **brand**, **price**, and a **image link**
