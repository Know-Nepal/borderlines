## Data Format
The file will be in `.json` and the format of the data will be as follows (_Extra fields may be added later_);

```json
{
  "cities": [
    {
      "name": "City name",
      "latitude": 0.0,
      "longitude": 0.0,
      "timezone": "Asia/Kathmandu",
      "officialLanguage": "Nepali",
      "currency": {
        "name": "Nepalese Rupee",
        "code": "NPR"
      },
      "landArea": {
        "value": 0.0,
        "unit": "km²"
      },
      "elevation": {
        "value": 1400,
        "unit": "metres"
      },
      "landmarks": [
        {
          "name": "Landmark 1",
          "latitude": 0.0,
          "longitude": 0.0
        },
        {
          "name": "Landmark 2",
          "latitude": 0.0,
          "longitude": 0.0
        }
      ]
    }
  ]
}
```


<h2>Contributing Guide</h2>

- Always create a relevant branch name.
- Use conventional commits whenever possible.
- Please check the correctness of data before contributing.
- Don't diverge from the format you're provided with.

_If you encounter any issues feel free to open an issue or ping us in the [Discord Server](http://discord.gg/7jwZaa8WDr)._