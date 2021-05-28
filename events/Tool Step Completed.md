# Tool Step Completed

## Javascript Code
```js
window.appEventData1848 = window.appEventData1848 || [];
appEventData1848.push({
  "event": "Tool Step Completed",
    "tool": {
        "responseIndustry": "<responseIndustry>",
        "toolStep": "<toolStep>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|responseIndustry|string||Agriculture, Healthcare, Financial Services|^[a-z]{2}([-]{1}[a-z]{2}){0,1}$||||||
