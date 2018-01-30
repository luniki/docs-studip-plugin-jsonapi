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
      "type": "document-folders",
      "id": "b819b13a4845547ed77db16f03969900",
      "attributes": {
        "name": "Kind 1",
        "description": null,
        "permission": "frwx",
        "mkdate": "2018-01-30T10:30:41+01:00",
        "chdate": "2018-01-30T10:30:41+01:00",
        "priority": 0
      },
      "relationships": {
        "documents": {
          "links": {
            "related": "https://example.com/document-folders/b819b13a4845547ed77db16f03969900/documents"
          }
        },
        "document-folders": {
          "links": {
            "related": "https://example.com/document-folders/b819b13a4845547ed77db16f03969900/document-folders"
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
        "parent": {
          "data": {
            "type": "document-folders",
            "id": "9414828f7dd9c36975ac44e464f68d9c"
          },
          "links": {
            "related": "https://example.com/document-folders/9414828f7dd9c36975ac44e464f68d9c"
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
        "self": "https://example.com/document-folders/b819b13a4845547ed77db16f03969900"
      }
    },
    "[...]"
  ]
}
```
