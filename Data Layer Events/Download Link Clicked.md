# Download Link Clicked

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "file_download",
  "detailed_event": "Download Link Clicked",
    "event_data": {
        "component_title": "<component_title>",
        "component_type": "<component_type>",
        "file_extension": "<file_extension>",
        "file_name": "<file_name>",
        "identifier": "<identifier>",
        "link_text": "<link_text>",
        "link_url": "<link_url>",
        "outbound": <outbound>,
        "region_ancestry": "<region_ancestry>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.component_title|string|The title of the component clicked.|success is not a location, we love sales people, customer stories|||||||
|event_data.component_type|string|The type of component a user clicks on.|visual\_cta, sub\_nav, hero\_banner, cta\_grid, footer\_nav|||||||
|event_data.file_extension|string|Captures the type of file that was downloaded \(i.e. PDF, EPUB, DMG\).|pdf, doc, csv, dmp, zip|||||||
|event_data.file_name|string|Captures the file name associated with file downloads.|Year End 2012.pdf, Operating Instructions.doc`|||||||
|event_data.identifier|string|Captures the ID associated with download links used.|act now, cancel, ok, 3456, 8765|||||||
|event_data.link_text|string|The text of the link clicked|watch video, watch now, grab the report|||||||
|event_data.link_url|string|Captures the site destination of the navigation links used.|https:\/\/www.example.com|||||||
|event_data.outbound|boolean|Whether the link leads to a different domain or not. \(boolean\)|false|||||||
|event_data.region_ancestry|string|Captures the name or ID of the region within which download links are used.|Top Nav, Footer Nav, Hero, Recommended, Also Shopped, Also Bought|||||||




