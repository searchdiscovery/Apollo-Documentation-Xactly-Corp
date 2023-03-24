# Form Submission Succeeded

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "form_complete",
  "detailed_event": "Form Submission Succeeded",
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
|event_data.form_type|string|Type of form viewed||||||||

## Attached Notes

<p>This snippet will fire if the form is successfully submited.</p>
<p>&nbsp;</p>
<p><img title="Form" src="https://github.com/searchdiscovery/Apollo-Documentation-Xactly-Corp/blob/main/Images/form.png?raw=true" alt="" /></p>
