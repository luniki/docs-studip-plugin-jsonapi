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
        "name-suffix": "",
        "global-permission": "root",
        "email": "root@localhost",
        "phone": null,
        "homepage": null,
        "address": null
      },
      "relationships": {
        "activitystream": {
          "links": {
            "related": "jsonapi.php/v1/users/76ed43ef286fb55cf9e41beadb484a9f/activitystream"
          }
        },
        "blubber-postings": {
          "links": {
            "related": "jsonapi.php/v1/blubber-postings?filter[user]=76ed43ef286fb55cf9e41beadb484a9f"
          }
        },
        "contacts": {
          "links": {
            "related": "jsonapi.php/v1/users/76ed43ef286fb55cf9e41beadb484a9f/contacts"
          }
        },
        "courses": {
          "links": {
            "related": "jsonapi.php/v1/users/76ed43ef286fb55cf9e41beadb484a9f/courses"
          }
        },
        "course-memberships": {
          "links": {
            "related": "jsonapi.php/v1/users/76ed43ef286fb55cf9e41beadb484a9f/course-memberships"
          }
        },
        "events": {
          "links": {
            "related": "jsonapi.php/v1/users/76ed43ef286fb55cf9e41beadb484a9f/events"
          }
        },
        "institute-memberships": {
          "links": {
            "related": "jsonapi.php/v1/users/76ed43ef286fb55cf9e41beadb484a9f/institute-memberships"
          }
        },
        "schedule": {
          "links": {
            "related": "jsonapi.php/v1/users/76ed43ef286fb55cf9e41beadb484a9f/schedule"
          }
        }
      },
      "links": {
        "self": "jsonapi.php/v1/users/76ed43ef286fb55cf9e41beadb484a9f"
      },
      "meta": [

      ]
    },
    "[...]"
  ]
}
```
