# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];;
dataLayer.push({ event_data: null });  // Clear the previous event_data object.;
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "page_load",
  "apollo_event": "Page Load Started",
    "ecommerce": {
        "page_type_merchandising": "<page_type_merchandising>"
    },
    "event_data": {
        "content_owner": "<content_owner>"
    },
    "page_data": {
        "bread_crumbs": "<bread_crumbs>",
        "country": "<country>",
        "language": "<language>",
        "page_location": "<page_location>",
        "page_name": "<page_name>",
        "page_name_detailed": "<page_name_detailed>",
        "page_title": "<page_title>",
        "page_type": "<page_type>",
        "site_name": "<site_name>",
        "site_section": "<site_section>",
        "site_type": "<site_type>",
        "sub_section": "<sub_section>",
        "sub_section_level_2": "<sub_section_level_2>",
        "sub_section_level_3": "<sub_section_level_3>",
        "url_full": "<url_full>",
        "url_hash": "<url_hash>",
        "url_path": "<url_path>",
        "url_query_string": "<url_query_string>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|bread_crumbs|string|Captures the postal code for shipping.|Home&gt;Women&gt;Tops&gt;Sweaters, Mens - Tops - Sweaters - Supmina, Wool, Rayon, Checkout &gt; Order Thank You|||||||
|content_owner|string|Counts of times the user performed an interaction on the order confirmation page.|XX product management, marketing, vendor name|||||||
|country|string|The country the site is associated with.||||||||
|language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.||||||||
|page_location|string|The url of the page currently being viewed.||||||||
|page_name|string|Amount of money discounted for the entire order.|product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|page_name_detailed|string|Captures the filter applied to the product listings or search results.|product - XYZ123 - super cotton neck scarf, Mens - Tops - Sweaters - Supmina, Wool, Rayon, Order Confirmation - 098fghjkl|||||||
|page_title|string|The title of the page currently being viewed, generally available in &lt;title&gt;.||||||||
|page_type|string|The type of page currently viewed.|home, pdp, article|||||||
|page_type_merchandising|string|Captures the revenue dollar amount of the order for use in bucketing orders into specific revenue bands \(i.e. $0-$50, $51-$100\).|Home, Event Detail, Property Detail, Product Listing, Blog Post, Shopping Cart|||||||
|site_name|string|Captures the business unit associated with each product.|Prospecting-EU, Prospecting-US, Member Portal, Shop-CA, Shop-US, Shop-EU|||||||
|site_section|string|The section of the site that the current page resides in. site\_section2 through site\_section5can also be used if the site has many sections.||||||||
|site_type|string|Amount of money associated with markdown prices for products reached the order confirmation step of the shopping cart.|Prospecting, Shop, Members, Brand|||||||
|sub_section|string|When a user has put in the information of an alternate pick up person during the checkout process.|Shop &gt; Kids, Shop &gt; Mens, Shop &gt; Womens|||||||
|sub_section_level_2|string|Captures the website or mobile app sub-sub-section \(two levels below main section\) associated with the page or screen viewed.|Shop &gt; Kids &gt; Tops, Shop &gt; Mens &gt; Shoes|||||||
|sub_section_level_3|string|Captures the website or mobile app sub-sub-sub-section \(three levels below main section\) associated with the page or screen viewed.|Shop &gt; Kids &gt; Tops &gt; Tees, Shop &gt; Mens &gt; Shoes &gt; Oxfords|||||||
|url_full|string|Captures the unique ID associated with each transaction.||||||||
|url_hash|string|Captures the coupon code associated with product level discounts for a transaction.||||||||
|url_path|string|Captures the path portion of the page URL.||||||||
|url_query_string|string|This parameter is already configured by Google Tag Manager and Google Analytics.||||||||




