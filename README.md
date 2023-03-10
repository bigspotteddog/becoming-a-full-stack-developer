# How to Become a Full Stack Developer

A project that I think would demonstrate great ability to do the job would be building something like a marketplace application along the lines of [amazon.com](https://amazon.com).

Here is something I have posted recently on the subject of being qualified...

# Part 1:

I feel  to be qualified for a junior level web developer position does not require as much material to be covered that seems to be prescribed. For full stack development, only a subset of each stack needs to be covered to handle about 90% of what you will be doing. The other 10% is project specific and that will need to be learned no matter how experienced you are.

Trimming what needs to be learned will dramatically cut down on the time it takes to become qualified and you can start productive learning by building something as you learn so it sticks quicker because you are using it as you learn it.

If you can build an e-commerce marketplace from scratch, similar to [amazon.com](https://amazon.com), I feel you would be more than qualified for a junior position and possibly even mid-level. And, think how great it will look in your portfolio. Here is a quick rundown of what skills I think you would need to build a site that works very much like amazon and this includes shopping cart, merchant product management, order processing. This list below also covers the project specific 10% for this project, payment processing and shipment tracking. Skills to learn:

* HTML
   * html, head, title, body, script, style
   * div, span, img, a, button, template
   * form, input, textarea, select, submit
* CSS
   * Class attribute
   * Stylesheet basics
   * Selectors
* Bootstrap
   * Layout: breakpoints, containers, grid, columns, gutters
   * Content: images, tables
   * Forms: form control, select, checks & radios, layout, validation
   * Components: breadcrumb, buttons, dropdowns, modal, pagination
   * Utilities: borders, colors, display, flex, float, text, vertical align
* JavaScript
   * Variables: var const let
   * Expressions and operators
   * Conditionals: if else, operators, switch
   * JSON: objects, arrays, parse, stringify
   * Loops: for, while
   * Functions (how to write and call a function)
   * Get element by id
   * Get elements by class
   * Template string substitution
   * Append element
   * REST: Fetch API GET, POST, PUT, DELETE requests
   * Stripe JS get credit card information
* Java/Spring Boot
   * Java
      * Installation
      * Variable types
      * Expressions and operators
      * Conditionals: if else, operators, switch
      * JSON: objects, arrays, fromJson, toJson
      * Loops: for, while
      * Functions (how to write and call a function)
      * Classes
   * Spring Boot
      * Create Spring Boot app
      * REST: receive HTTP GET, POST, PUT, DELETE requests
      * Connect to database
   * Select, insert, update, delete information from database
   * Stripe API submit payment
   * Get shipment tracking information from UPS/FedEx/USPS
* Database
   * Install database
   * Create table
   * Create index
   * Normalization
   * SQL
      * select, join, where, order by, group by, sum
      * insert
      * update, where
      * delete, where
* Testing

# Part 2:

You might not know where to start when building something this full featured. And, you can build something like this even as a beginner.

Here is a quick description:

# How to build an e-commerce marketplace website from scratch

Even a beginner can learn how to build an e-commerce marketplace website from scratch. Take it one step at a time and build upon it and your knowledge. The website described here will work similar to Amazon Fresh.

The features for this e-commerce site are described below. The skills needed to complete this project are above.

## Prerequisites

The first step will be to deploy a "Hello World!" web application to the cloud. A web application includes a backend system where a website does not. You will learn some dev ops to get the web site deployed. Start small and incrementally improve the website from there.

## Application server

Learn Java for the backend programming language and Spring Boot as the application server. You will need to install Java and run the Spring Boot initializer to create the initial application.

## Google Cloud Platform

Since this e-commerce store will be deployed to the cloud, you will learn Google Cloud Platform (more beginner friendly than AWS) and you will need to install that and its prerequisite, Python.

Once you have installed these platform tools, you will publish the web application to GCP on Google App Engine. You will want the e-commerce store to be secure so you will need to issue and configure the web application to use a SSL/TLS certificate. You will also need to register a domain and configure DNS settings.

You will also learn how to setup a database.

## What are the features of this e-commerce website?

The following is a list of features for an e-commerce website.

## Customer view

Customers should be able to view and buy products whether they logged in or not.

Logged in customers will be able to view their current open orders as well as their past orders. Customers can also save products in their shopping cart and move products to save for later.

We should display a recently viewed product history for logged in customers too.

Customers will browse products by category as the default view. Customers can run a keyword search which will list all products scoring greater than zero sorted by search score.

Payment and shipping addresses should be saved for logged in customers.

## Browse products by category

This is the default view.

Customers should be able to see products by category. Categories can be in rows with products in the category in columns. Scrolling through the products in a category can work like amazon fresh.

Categories can have subcategories. When a customer is browsing products, they can click on a category and the view will change to rows of subcategories within the category clicked.

## Search for products by keyword

There should be a keyword search at the top of the page. Products getting a search score greater than zero will be displayed in descending score order.

## View product

When a customer clicks on a product while browsing, they will be taken to the product view which will have a title, description, price, options, and images.

## View shopping cart

When a customer adds a product to their shopping cart, a counter will be displayed at the top of the page. When the customer clicks on the cart, the items in the cart will be displayed. Customers should be able to change item quantities there and they should be able to remove products.

## Checkout

When a customer is viewing their cart, they will have the option to checkout. On the checkout page, the customer can add the shipping address and payment information. If the customer is logged in, they can pick between previously saved shipping addresses and payment information.

## Product reviews

Products will have customer reviews that have a star rating, a heading and a comment. This should appear at the bottom of the product page.

## Login

A customer can login to view their shopping cart and can track their current and previous orders.

## Save for later

When a customer is logged in and viewing items in their shopping cart, they can move an item to save for later.

## My orders

When a customer is logged in they can view their order history.

## Track orders

When a customer is logged in they can track orders in their order history.

## Merchant view

Whether this e-commerce website has a single seller or it is a marketplace, we will build it as a marketplace. Merchants should be able to register and sell their products on the store.

Merchants can build their own store too. If a customer clicks on a merchants page link, the products displayed will be those of the merchant selected.

## Add products

A merchant can add products to their store and they will show up on the main store. Products can have a title and description. A product can also have multiple options and prices. Maybe there should be a default product price that is overridden or added to by the options. This means an option price can be absolute or additive.

## Categorize products

A merchant can assign products to a category that will make it easier for customers to find a product.

## Process orders

When a customer places and order, the merchant needs to process and ship the order. When logged in a merchant can view their current orders, select them for processing, the mark them as shipped with tracking information.

## Modify orders

Merchants may need to modify orders to process refunds, give discounts, or other customer service activities.

## Merchant settings

Merchants will need to setup the Stripe checkout information so they can receive payment for products sold.

# Notes

This looks like a long list; however, about 90% of what is described here is simple CRUD. You learn how to do REST to CRUD one time, then repeat it for almost every feature in this list. The other 10% is payment processing and shipment tracking. Also, not too difficult and you only need to learn each of those once.

Pick and choose what to learn first here and you do not need to do all of it. Just being able to add products for sale and allow someone to buy products is the MVP (Minimum Viable Product). Everything else is additional learning.
