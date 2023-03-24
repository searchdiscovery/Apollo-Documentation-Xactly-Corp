# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "page_load_started",
  "detailed_event": "Page Load Started",
    "page_data": {
        "breadcrumb": "<breadcrumb>",
        "country": "<country>",
        "language": "<language>",
        "page_location": "<page_location>",
        "page_title": "<page_title>",
        "site_section": "<site_section>",
        "site_section2": "<site_section2>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page_data.breadcrumb|string|A delimited list of hierarchical sections that describe the current page's location within the navigation of the site.|Home&gt;Women&gt;Tops&gt;Sweaters, Mens - Tops - Sweaters - Supmina, Wool, Rayon, Checkout &gt; Order Thank You|||||||
|page_data.country|string|The country associated with the current page.|US, CA, FR, UK|||||||
|page_data.language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.|en-us, en-gb, ch-cn, fr-ca, fr-fr|||||||
|page_data.page_location|string|The url of the page currently being viewed.||||||||
|page_data.page_title|string|The title of the page currently being viewed, generally available in &lt;title&gt;.||||||||
|page_data.site_section|string|The section of the site that the current page resides in. site\_section2 through site\_section5can also be used if the site has many sections.||||||||
|page_data.site_section2|string|Captures the sub-section of the site where the page being viewed is located|Shop &gt; Kids, Shop &gt; Mens, Shop &gt; Womens|||||||

## Attached Notes

<p>This snippet will load at the beginning on the page and contain all the information about the page</p>
<p>Page Load Started &gt; Page Load Completed</p>
