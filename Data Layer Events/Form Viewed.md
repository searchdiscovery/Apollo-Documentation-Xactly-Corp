# Form Viewed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "form_view",
  "detailed_event": "Form Viewed",
    "event_data": {
        "form_name": "<form_name>",
        "form_type": "<form_type>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.form_name|string|Name of the form|webinar, download white paper, request demo|||||||
|event_data.form_type|string|Type of Form|lead\_gen, contact|||||||

## Attached Notes

<p>This snippet will fire if the form component enters the user's viewport. This will only fire one time on the page.</p>
<p>&nbsp;</p>
<p><img title="Form" src="https://github.com/searchdiscovery/Apollo-Documentation-Xactly-Corp/blob/main/Images/form.png?raw=true" alt="" /></p>
