# Inventaire

## Pricing

\[COMPLETE DESCRIPTION HERE\]

* The price of a product is done within the stock screen.
* The price can differ based on variant.
* We should categorize clients based on volume.
* We should be able to price a product for a specific client.

## SKU and UPC

While some may haphazardly interchange the terms UPC and SKU, they are actually two quite different entities. They are both numeric-based codes assigned to products, but UPCs, or Universal Product Codes are standardized for business use and provide a product description that, once scanned, anyone could read. In contrast, a SKU, or Stock Keeping Unit, is a number assigned to a product by the company for stock-keeping purposes and internal operations.

The UPC code is affixed to a product wherever it is sold, remaining a constant throughout the product’s shelf life. Since a SKU is unique to the company, the same product would have different SKUs if sold by different companies, but they would have the same UPC.

Another difference is that SKUs are typically eight alpha-numeric digits, while UPCs are 12 digits, numeric only.

In conclusion, SKUs are for internal use, and UPCs are for external, or universal, use.

## Stock Control

Stock control, also known as inventory control, is used to show how much stock you have at any one time, and how you keep track of it. It applies to every item you use to produce a product or service, from **raw materials** to **finished goods**. It covers stock at every stage of the production process, from **purchase** and **delivery** to **using** and **re-ordering** the stock.

{% page-ref page="stock-control.md" %}

## Variant

Variants are different version of the same product. They ease the creation of products that keep the same characteristics with minor changes. A good example would be the production of clothes. The design and material is the same, but the color or the size could change.

The pricing of variant is important. A variant can be priced directly within the stock screen or use the price of the parent product. The user should always be able to determine if a variant have it's own price or if the price comes from the parent.

{% page-ref page="variantes.md" %}

## Assembly or Composite

\[Complete description\]

## Cost

Each stock can have their own cost according to the price they are bought for. The system offers three different ways of handling costs within the stock. Each of the cost variables are stored with dates of changes so the user can track back costs. The system also keep tracks of them and help the users take decisions based on those costs fluctuations.

The first one being the average cost of the item that determine what should be the cost of a specific cost when a buyer purchase it in average this cost is either manually entered or taken from all the purchase orders of the stock.

The last cost is the cost of the item for the latest purchase order. This cost help the buyer predict what would be a good or not good cost for the product when buying it. It also provide a way of determining if the current cost of a purchase order is too expensive.

\[REVISED THIS\] The next cost is a calculated cost based on all the fees and the real cost that was charged to the company when it received the last stock.

## Moving

## Warehouse and Localization

Warehouse are used to determine a place where stocks are being held. These allow the administrators and managers to keep inventory quantities above a certain threashold at each places and manage their point of sales with a better consistancy.

A stock could have quantities in multiple warehouse and localization.

### Localization

The localization are places within a warehouse such as shelf, boxes, yards, silo, etc.

## Automation

\[Complete description\]

