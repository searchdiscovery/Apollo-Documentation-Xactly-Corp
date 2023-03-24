# Form Field Engaged

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "form_field_interaction",
  "detailed_event": "Form Field Engaged",
    "event_data": {
        "field_name": "<field_name>",
        "form_name": "<form_name>",
        "form_type": "<form_type>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.field_name|string|Captures the name of the Field that a user engages with.||||||||
|event_data.form_name|string|Name of the form|webinar, download white paper, request demo|||||||
|event_data.form_type|string|Type of form viewed||||||||




