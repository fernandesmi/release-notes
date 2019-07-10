# Product Identifier component

It is possible to now display a product identifier on your Product Details page.

<img width="211" alt="product-identifier-component" src="https://user-images.githubusercontent.com/52087100/60997935-62a03380-a32e-11e9-9c3b-754fdc01ec7d.png">

The [new Product identifier](https://github.com/vtex-apps/product-identifier) component can be configured to display the following product identifier options:

- Product Reference

- Product ID

- SKU EAN

- SKU Reference


## What has changed

Prior to this release, the products/SKU IDs and references weren’t available anywhere else on the store’s site.


## Main advantages

By displaying an official ID or Reference, the user can easily refer to the product or SKU through any of the store’s available communication channel, improving their buying experience.

In addition, this block is useful for providing extra flexibility in the store layout since it can be placed anywhere when combined with the Product Details page flex layout.


## What you need to do

To add Product Identifier to your store, follow the steps below:

__1.__ Add `"vtex.product-identifier": "0.x"` to your `manifest.json` dependencies

__2.__ Place the `product-identifier` block in your [Product Details](https://github.com/vtex-apps/product-details) page section in the `blocks.json` file

__3.__ Customize the field label and the ID type that should be shown on the store front