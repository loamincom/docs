# How do I use Loamin?

Start here.

```py
import requests

requests.post(url, body)
```

We have algorithms for XX and YY purposes.

Example of a Run response:

```json
{
    "run": {
        "apiuser_id": 0,
        "algo_id": "soil_oc_stock:2",
        "hectares": 18.851485702191138,
        "run_status": "success",
        "created_at": "2024-04-16T16:03:23.416889+00:00",
        "id": "ru-4r3LotCNC8f",
        "source_id": "test_area",
        "response_path": "/run/ru-4r3LotCNC8f"
    },
    "payload": {
        "areas": {
            "hectares": 18.851485702191138,
            "sq_km": 0.18851485702191137,
            "sq_m": 188514.85702191136,
            "perimeter_km": 1.982992962847892,
            "perimeter_m": 1982.992962847892
        }
    },
    "assets": {
        "prediction_combined.geojson": "<SIGNED URL>",
        "prediction_combined.tif": "<SIGNED URL>",
        "prediction_combined_interpolated.tif": "<SIGNED URL>"
    }
}
```
