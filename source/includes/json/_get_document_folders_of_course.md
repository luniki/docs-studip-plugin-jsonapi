```json
{
  "meta": {
    "page": {
      "offset": 0,
      "limit": 30,
      "total": 1
    }
  },
  "links": {
    "first": "/?page[offset]=0&page[limit]=30",
    "last": "/?page[offset]=0&page[limit]=30"
  },
  "data": [
    {
      "type": "document-folders",
      "id": "4e06de84a2812908879eef42c9d652d9",
      "attributes": {
        "name": "Allgemeine Dateien",
        "description": "Allgemeine Beschreibung",
        "permission": "frwx",
        "mkdate": "2018-01-24T12:08:38+01:00",
        "chdate": "2018-01-24T12:08:38+01:00",
        "priority": 0
      },
      "relationships": {
        "documents": {
          "links": {
            "related": "https://example.com/document-folders/4e06de84a2812908879eef42c9d652d9/documents"
          }
        },
        "document-folders": {
          "links": {
            "related": "https://example.com/document-folders/4e06de84a2812908879eef42c9d652d9/document-folders"
          }
        },
        "owner": {
          "data": {
            "type": "users",
            "id": "e7a0a84b161f3e8c09b4a0a2e8a58147"
          },
          "links": {
            "related": "https://example.com/users/e7a0a84b161f3e8c09b4a0a2e8a58147"
          }
        },
        "range": {
          "data": {
            "type": "courses",
            "id": "a07535cf2f8a72df33c12ddfa4b53dde"
          },
          "links": {
            "related": "https://example.com/courses/a07535cf2f8a72df33c12ddfa4b53dde"
          }
        }
      },
      "links": {
        "self": "https://example.com/document-folders/4e06de84a2812908879eef42c9d652d9"
      }
    }
  ]
}
```
