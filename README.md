# Berlin Coworking spaces
A curated list of coworking spaces in Berlin, Germany.


## Contribution Guidelines

Please ensure your pull request adheres to the following guidelines:

- Search previous entries before making a new one, as yours may be a duplicate.
- Make sure your contribution is useful before submitting.
- Check your spelling and grammar.

**Working on your first Pull Request?** You can learn how from this free series [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github).



## Description
This Json version uses the GeoJSON http://geojson.org/ format is an array of objects including the following shape:

- Day rate for a desk
- Monthly rate for a flex desk
- Monthly rate for a fixed desk

```
[
{
    "type": "Feature",
    "properties": {
      "name": "",
      "website": "",
      "description": "",
      "address": {
        "street": "",
        "postcode": "",
        "city": "",
        "country": "country 2 digit ISO code"
      },
      "rates": {
        "day": "",
        "flex": "",
        "fixed": ""
      }
    },
    "geometry": {
      "type": "Point",
      "coordinates": [
        "longitude",
        "latitude"
      ]
    }
  ...
]
```

## License
This add-on has been released under GNU General Public License v3.0
