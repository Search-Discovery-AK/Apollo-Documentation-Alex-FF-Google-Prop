# Download Link Clicked

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];;
dataLayer.push({ event_data: null });  // Clear the previous event_data object.;
dataLayer.push({
  "event": "select_content",
  "apollo_event": "Download Link Clicked",
    "event_data": {
        "download_link_click_event": "<download_link_click_event>",
        "download_link_container": "<download_link_container>",
        "download_link_id": "<download_link_id>",
        "download_link_region": "<download_link_region>",
        "downloaded_file_count_lifetime": "<downloaded_file_count_lifetime>",
        "downloaded_file_count_visit": "<downloaded_file_count_visit>",
        "downloaded_file_name": "<downloaded_file_name>",
        "downloaded_file_type": "<downloaded_file_type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|download_link_click_event|string|Captures the recurring frequency of donation \(i.e. one-time, monthly\).||||||||
|download_link_container|string|Captures the state or province associated with payments used for a transaction \(i.e. order, booking, dontation, etc.\).|Best Friends - Best Jeans, Puppy Love, Sail Away, Mens, Kids, Kids : Tops|||||||
|download_link_id|string|Count of times that users completed the donation process.|act now, cancel, ok, 3456, 8765|||||||
|download_link_region|string|Captures the currency used for currency-related actions.|Top Nav, Footer Nav, Hero, Recommended, Also Shopped, Also Bought|||||||
|downloaded_file_count_lifetime|string|Count of donations completed that incuded a card request.||||||||
|downloaded_file_count_visit|string|Captures a unique ID for each donation transaction.||||||||
|downloaded_file_name|string|Captures the postal code associated with a transaction \(i.e. order, booking, dontation, etc.\).|Year End 2012.pdf, Operating Instructions.doc`|||||||
|downloaded_file_type|string|Captures the city associated with a payment.|pdf, doc, csv, dmp, zip|||||||




