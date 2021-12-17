# User Detected

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];;;
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "user_detected",
  "apollo_event": "User Detected",
    "page_data": {
        "affiliate_customer_id": "<affiliate_customer_id>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliate_customer_id|string|The user ID of user who arrived at the website via a third party partner.||||||||




