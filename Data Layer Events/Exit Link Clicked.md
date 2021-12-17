# Exit Link Clicked

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];;
dataLayer.push({ event_data: null });  // Clear the previous event_data object.;
dataLayer.push({
  "event": "select_content",
  "apollo_event": "Exit Link Clicked",
    "event_data": {
        "exit_link_click_event": "<exit_link_click_event>",
        "exit_link_container": "<exit_link_container>",
        "exit_link_id": "<exit_link_id>",
        "exit_link_region": "<exit_link_region>",
        "exit_link_target": "<exit_link_target>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|exit_link_click_event|string|Count of times that each event detail option is displayed||||||||
|exit_link_container|string|Count of times that event detail pages were viewed.|Best Friends - Best Jeans, Puppy Love, Sail Away, Mens, Kids, Kids : Tops|||||||
|exit_link_id|string|Amount of money associated with an event booking at the time of booking start.|act now, cancel, ok, 3456, 8765|||||||
|exit_link_region|string|Captures the total number of event detail options returned.|Top Nav, Footer Nav, Hero, Recommended, Also Shopped, Also Bought|||||||
|exit_link_target|string|Count of times that event detail options were selected|https:\/\/www.usda.gov. https:\/\/msnbc.com|||||||




