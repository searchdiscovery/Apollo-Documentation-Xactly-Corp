# Scroll Depth

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "scroll_depth",
  "detailed_event": "Scroll Depth",
    "event_data": {
        "milestone": "<milestone>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.milestone|string|This will contain the scroll depth milestone|25, 50, 75, 100|||||||

## Attached Notes

<p>Fire when the user scrolls down the page on 25, 50, 75, 100 percent of the page</p>
