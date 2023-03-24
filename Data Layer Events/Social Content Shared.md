# Social Content Shared

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "share",
  "detailed_event": "Social Content Shared",
    "event_data": {
        "method": "<method>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.method|string|Captures the name of the social network associated with social network activity \(i.e. follow, share\).|facebook, linkedIn, instrgram, twitter|||||||

## Attached Notes

<p>This snippet will fire on any social links.</p>
<p>&nbsp;</p>
<p><img title="social_link" src="https://github.com/searchdiscovery/Apollo-Documentation-Xactly-Corp/blob/main/Images/social_buttons.png?raw=true" alt="" /></p>
