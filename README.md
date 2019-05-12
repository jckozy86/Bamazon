# Barmazon

Week 12 Node &amp; SQL hw - Amazon store CLI

## Pre-requisites

If you have already installed yarn, ignore the following instructions and go to the next step

* Windows Users: Install Yarn [here](https://yarnpkg.com/latest.msi).
* Mac Users: Using Homebrew Install Yarn like this: `brew install yarn`

## Using The Application

In order to use the app, you need to download all the files from github, and then run `yarn install`

Once complete you can run: node bamazonCustomer.js

### Purchase items

When you first start the app you will get a list of all the items the Bamazon store as seen below:

`
ID: 1, Product: iphone, Department Name: electronics, Price: 1000, Available Quantity: 7
ID: 2, Product: imac, Department Name: electronics, Price: 2000, Available Quantity: 15
ID: 3, Product: XZ5 Compact, Department Name: electronics, Price: 1000, Available Quantity: 100
ID: 4, Product: Learning Javascript for Dummies, Department Name: books, Price: 5.99, Available Quantity: 50
ID: 5, Product: How to Hack GitHub, Department Name: books, Price: 4.99, Available Quantity: 15
ID: 6, Product: No Comment T-Shirt, Department Name: clothing, Price: 19.99, Available Quantity: 20
ID: 7, Product: Diesel Logo T-Shirt, Department Name: clothing, Price: 1000, Available Quantity: 100
ID: 8, Product: LG UHD 65", Department Name: tv, Price: 2199.99, Available Quantity: 3
ID: 9, Product: LG UHD 55", Department Name: tv, Price: 1600, Available Quantity: 8
ID: 10, Product: Balenciaga, Department Name: HandBags, Price: 1000, Available Quantity: 0
`

The application will then ask for the item the user wishes to order by giving a list of items.
This list shows the ID and the name of the item.

The application will then ask for the quantity that he wishes to purchase.


## Output

Once the item selection and quantity is selected, the application will show the total cost the user spent.
If the user chose a quantity larger than what is in stock, the user will get a message showing insufficient quantity.

## Instructional Video

An instructional video can be found at: [demo video](https://drive.google.com/open?id=1SFuaVYGJLrpn2YztXAp54WYCWqRTOzMa)

## Folder and file Structure

```
bamazonCustomer.js -> main file to run
schema_seed.sql -> SQL file to create and populate the SQL DB
package.json -> file containing all dependencies
yarn.lock -> file containing exact module version dependencies
```
For purposes of this project working, please do not change file names or folder locations.

### Thanks for checking my application :D
