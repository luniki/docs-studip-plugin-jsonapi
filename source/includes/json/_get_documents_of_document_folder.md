```json
{
  "meta": {
    "page": {
      "offset": 0,
      "limit": 30,
      "total": 2
    }
  },
  "links": {
    "first": "/?page[offset]=0&page[limit]=30",
    "last": "/?page[offset]=0&page[limit]=30"
  },
  "data": [
    {
      "type": "documents",
      "id": "1a7be00625cb1b71cdf113b3d4d42957",
      "attributes": {
        "name": "Dateiname1",
        "description": "Dateibeschreibung 1",
        "filename": "Dateiname1",
        "mkdate": "2018-01-30T10:35:54+01:00",
        "chdate": "2018-01-30T10:35:54+01:00",
        "filesize": 17,
        "downloads": 0,
        "priority": 0
      },
      "relationships": {
        "parent": {
          "data": {
            "type": "document-folders",
            "id": "8ed90d64dfdc754e6fd6cc5bdcbbc5c9"
          },
          "links": {
            "related": "https://example.com/document-folders/8ed90d64dfdc754e6fd6cc5bdcbbc5c9"
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
        },
        "owner": {
          "data": {
            "type": "users",
            "id": "e7a0a84b161f3e8c09b4a0a2e8a58147"
          },
          "links": {
            "related": "https://example.com/users/e7a0a84b161f3e8c09b4a0a2e8a58147"
          }
        }
      },
      "links": {
        "self": "https://example.com/documents/1a7be00625cb1b71cdf113b3d4d42957"
      },
      "meta": {
        "download-url": "https://example.com/documents/1a7be00625cb1b71cdf113b3d4d42957/content"
      }
    },
    "[...]"
  ]
}
```
