#Google Shopping (Ruby)

## Now with 100% more Ruby and 100% less JavaScript

You've already done it in JavaScript... now lets try it again in Ruby. This will help you get ready to dive into Ruby and should teach you how to be *resourceful*.

Google and Ruby's documentation have all of the answers. Start slow and use smart searching for things like...

* Filtering an array in Ruby
* Mapping an array in Ruby
* Iterating over a hash in Ruby

##Getting Started

* Fork and clone this repo
* Run `bundle install` to install dependencies
  * This installs gems. Gems are packages, and are installed using bundler.
* Run the file by typing `ruby lib/google_shopping.rb`
  * Run `rubocop` to lint your code

##Assignment (Déjà vu)

Use the product search result in your file to check the following:

1.) The `kind` of results you're are dealing are `shopping#products`. Go through the `items` and find all results that have `kind` of `shopping#product`. How many are there? Where else is this count information stored in the search results?

2.) Find all items with a `backorder` availability in `inventories`.

3.) Find all items with more than one image link.

4.) Find all `canon` products in the items (careful with case sensitivity).

5.) Find all `items` that have **product** **author** **name** of "eBay" and are brand "Canon".

6.) Print all the products with their **brand**, **price**, and a **image link**
