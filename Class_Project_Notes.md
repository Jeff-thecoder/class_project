♦ 4     • 7      ◘ 8     ○ 9      ◙ 10     ► 16     » 175     ∙ 249      ■  254

First task is to create a team:

- the instructor is the P/O
- 1 Scrum Master
- A Tech Lead
- Developers


Business name:
Scott's Really Cool Gadgets

- Current infrastructure is a bunch of manuel systems that are not working well
- He needs:

  • As a business I owner I want to know my PROFIT/LOSS 



• Ability to take orders, have a pick sheet automatically created, and a shipment prepared
• When a shipment is made, the inventory must be updated
• We will need to track customer organizations and the customers themselves
• When a payment is made the order needs to be completed


   ♦ We need a completely new database from old school inventory design
   ♦ Admin Page for inventory manager/owner
   ♦ Have Website that can call and update Backend ( Node/etc... )


### 1.  App / Home.view    - Customer visits website


4 - As a customer I want to see what I'm buying because I don't like buying without seeing it.
2 - As a customer I want to know if product is in stock so I can know if I can buy it.
4 - As a customer I want to know when I can get my item so I can know when to expect it.
	As a user I want to be able to track order so I know when it will arrive.
	As a user I want to be able to return or replace the item if I don't like it.
 
	As a user I want to be able to see the price so I know if I would like to buy it.
	As  user I want to be able to compare prices so that I know I'm getting the best price.
	As an inventory manager I want to be able to update the database so I know products are in stock or not.
	As a inventory manager I want to have a running inventory available so I can know the current inventory available.
	As a inventory manager I want the feature of having automatic reorder so we have stoock on hand.
	As a inventory manager I want to be able to keep track of receuiver shipments so I can keep track of our supplies.
	As an inventory manager I want to make sure that only one customer can add the last item to their cart, so we don't sell out of stock item


### 2.  FindProduct.view - Find Customer Searched Item

5 -  As a user I want the search list to self populate so that I can have recommendations
3 -  As a customer I want to be able to type in ther name of the item so I can find it easily
3 -  As a customer I want  to be able to have a list of attributes so I can find it
As a customer I want to have automatic item recomendations so I can realize what I might want
As a customer I want to be able to see a product view history so I know what I already searched for


### 3.  DisplayUserItem.view

2  - As a user I want to be able to see the price so I know if I would like to buy it.
2  - As a user I want to be able to see details of the product so I am more informed about the item
2 -  As a user I want to see the product specs so I can know how well the item performs/etc.
As a user I want to have options so that I can pick colors/size/function/etc.

As a customer I want to see what I'm buying because I don't like buying without seeing it.

### 4.  If Customer wants product, CheckInventory 

As a product ower I want to know inventory so I know that we are not selling an out of stock item
As a user I want to know if an item is low on stock so I know how the quantity
As  a customer I want to know if a product is returnable so I can return it if needed



### 5.  AddToCart 

As a user I want an add to cart button so I can save the product and continue shopping
As a user I don't want to be able to add to cart so that I don't pay for something that is not available, so that I'm not charged
As  user I want to be able to see what is in my cart so that I can see what I'm buying
As user I want to have a confirmation page between payment and buying so that I can change my mind
As a user I want to be able to delete an item so that I can update my shopping cart


### 6.  Signup, Sign-in Page

As a customer I want to have a centralized place to see my orders so that I know what I'm about to order.
As a customer I wan to be able to signin so that I have a secure transaction
As  customer I wan to be able to sign-up so that I can place orders



♦  Up-sell them additional items

ManageProduct---
7.  PlaceOrder
8.  MakePayment
9.  Arrange Warehouse Shipping
10. MakeShipment
11. Email Customer Tracking


Other things needed:

CancelOrder
SubmitReview

♦ Secure Website

As a owner I want to have an admin page so that I can update the database when needed
As an owner I want to have an outside source that handles CC number so that I will not be held accountable for stolen info