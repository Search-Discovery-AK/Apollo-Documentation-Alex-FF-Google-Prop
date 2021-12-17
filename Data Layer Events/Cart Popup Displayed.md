# Cart Popup Displayed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.;;
dataLayer.push({
  "event": "view_cart",
  "apollo_event": "Cart Popup Displayed",
    "ecommerce": {
        "cart_id": "<cart_id>",
        "cart_popup_displayed": "<cart_popup_displayed>",
        "currency": "<currency>",
        "items": [
            {
                "item_id": "<item_id>",
                "item_name": "<item_name>"
            }
        ],
        "value": <value>
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|cart_id|string|Captures the name or ID of the region within which CTA links are used.|12345, 435678, 34567, XCV456, XCV876|||||||
|cart_popup_displayed|unknown|Count of orders taking place offline from internal databases for use in comparing to online orders.||||||||
|currency|string|The currency, in 3-letter ISO 4217 format.||||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\) |SKU\_12345|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|value|number|The monetary value of the event.	|7.77, 239.55, 659|||||||




