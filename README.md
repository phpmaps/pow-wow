pow-wow
=======

Realator App Entry for Hackathon

##Template-ify

###Option 1 - includes html fragement based driven slides [notes](http://dojotoolkit.org/reference-guide/1.9/dojox/mobile/dynamic-content-loading.html#load-content-into-existing-view-and-perform-transition)

```javascript
{
    "fragementPath":"http://.../project/fragements/",
    "items": [
        {
            "enrichType": "schools",
            "requestUrl": "http://some/arcgis/geoenrich/endpoint",
            "priority": 5,
            "distance": 2,
            "kpi":["field1","field2","field3"],
            "fragementName":"three-rows.html"
        },
        {
            "enrichType": "household income",
            "requestUrl": "http://some/arcgis/geoenrich/endpoint",
            "priority": 4,
            "distance": 2,
            "kpi":["field1"],
            "fragementName":"single-value.html"
        }
    ]
}
```
