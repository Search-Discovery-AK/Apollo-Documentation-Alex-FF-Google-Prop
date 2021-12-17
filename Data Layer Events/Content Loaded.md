# Content Loaded

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];;
dataLayer.push({ event_data: null });  // Clear the previous event_data object.;
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "content_loaded",
  "apollo_event": "Content Loaded",
    "event_data": {
        "content_date_merchandising": "<content_date_merchandising>",
        "content_id": "<content_id>",
        "content_id_merchandising": "<content_id_merchandising>",
        "content_licensor": "<content_licensor>",
        "content_modified_date": "<content_modified_date>",
        "content_publish_date": "<content_publish_date>",
        "content_title": "<content_title>",
        "content_title_merchandising": "<content_title_merchandising>"
    },
    "page_data": {
        "content_author": "<content_author>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|content_author|string|The context in which the listing is displayed \(Onsite Search, Curated Assortment,  Navigation\)|Betsy Ross, Ben Franklin, Howard Hughes, Tipper Gore|||||||
|content_date_merchandising|string|The sort value selected by default on listings.|2001-12-22, 2011-01-01|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||
|content_id|string|Captures the unique ID of content items \(i.e. article or blog post\).||||||||
|content_id_merchandising|string|Captures the optimization test IDs as concatenated list for active tests.||||||||
|content_licensor|string|Count of content listings displayed in content listings.|HBO, Disney|||||||
|content_modified_date|string|Captures the number of content items displayed in a content listing.|1-1-2020, 2-2-2019|||||||
|content_publish_date|string|Captures the author associated with website or mobile app content \(i.e. article, blog post\).|2001-12-22, 2011-01-01|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||
|content_title|string|Count of times that visitors viewed content listings.|50 ways to use jello, Another look at pandas, Year end giving|||||||
|content_title_merchandising|string|Count of times when visitors began a contact request flow.|50 ways to use jello, Another look at pandas, Year end giving|||||||




