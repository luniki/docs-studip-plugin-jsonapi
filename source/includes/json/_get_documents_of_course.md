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
      "type": "documents",
      "id": "210ea083325e12fdb2dd6eaa534d0570",
      "attributes": {
        "name": "test.json",
        "description": "Eine Beschreibung",
        "filename": "test.json",
        "mkdate": "2018-01-24T09:52:13+01:00",
        "chdate": "2018-01-24T09:52:13+01:00",
        "filesize": 17,
        "downloads": 0,
        "priority": 0
      },
      "relationships": {
        "parent": {
          "data": {
            "type": "document-folders",
            "id": "b0243fbbd542ffa5d00eca4791540f03"
          },
          "links": {
            "related": "https://example.com/document-folders/b0243fbbd542ffa5d00eca4791540f03"
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
        "self": "https://example.com/documents/210ea083325e12fdb2dd6eaa534d0570"
      },
      "meta": {
        "download-url": "https://example.com/documents/210ea083325e12fdb2dd6eaa534d0570/content"
      }
    }
  ]
}
```
