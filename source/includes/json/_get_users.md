```json
{
  "meta": {
    "page": {
      "offset": 0,
      "limit": 30,
      "total": 5
    }
  },
  "links": {
    "first": "/?page[offset]=0&page[limit]=30",
    "last": "/?page[offset]=0&page[limit]=30"
  },
  "data": [
    {
      "type": "users",
      "id": "76ed43ef286fb55cf9e41beadb484a9f",
      "attributes": {
        "username": "root@studip",
        "formatted-name": "Root Studip",
        "family-name": "Studip",
        "given-name": "Root",
        "name-prefix": "",
        "name-suffix": ""
      },
      "relationships": {
        "activitystream": {
          "links": {
            "related": "https://example.com/users/76ed43ef286fb55cf9e41beadb484a9f/activitystream"
          }
        },
        "blubber-postings": {
          "links": {
            "related": "https://example.com/blubber-postings?filter[user]=76ed43ef286fb55cf9e41beadb484a9f"
          }
        },
        "contacts": {
          "links": {
            "related": "https://example.com/users/76ed43ef286fb55cf9e41beadb484a9f/contacts"
          }
        },
        "courses": {
          "links": {
            "related": "https://example.com/users/76ed43ef286fb55cf9e41beadb484a9f/courses"
          }
        }
      },
      "links": {
        "self": "https://example.com/users/76ed43ef286fb55cf9e41beadb484a9f"
      }
    },
    "[...]"
  ]
}
```
`