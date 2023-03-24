# CTA Link Clicked

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "click",
  "detailed_event": "CTA Link Clicked",
    "event_data": {
        "component_title": "<component_title>",
        "component_type": "<component_type>",
        "identifier": "<identifier>",
        "link_text": "<link_text>",
        "link_url": "<link_url>",
        "outbound": <outbound>
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.component_title|string|The title of the component clicked.|success is not a location, we love sales people, customer stories|||||||
|event_data.component_type|string|The type of component a user clicks on.|visual\_cta, sub\_nav, hero\_banner, cta\_grid, footer\_nav|||||||
|event_data.identifier|string|Captures the ID associated with CTA links used.|act now, cancel, ok, 3456, 8765|||||||
|event_data.link_text|string|The text of the link clicked|watch video, watch now, grab the report|||||||
|event_data.link_url|string|Captures the site destination of the navigation links used.|https:\/\/www.example.com|||||||
|event_data.outbound|boolean|Whether the link leads to a different domain or not. \(boolean\)|false|||||||

## Attached Notes

<p>Add the code snippet below such that it executes when a callout is clicked.</p>
<p>&nbsp;</p>
<p><img title="Callout Tracking" src="https://github.com/searchdiscovery/Apollo-Documentation-Xactly-Corp/blob/main/Images/visual_cta_1.png?raw=true" alt="" /></p>
