REST API Small Task

| Description  | Method | HTTP Request|
| ------------- | ------------- |------------- |
| Get list of countries  | GET  |GET /restapi/country HTTP 1.1 <br /> Host: my.site.com <br /> User-Agent: Internet-Explorer 9.0 |
| Get list of hotels in country  | GET  | GET /restapi/hotel/country/ukraine HTTP 1.1 <br /> Host: my.site.com <br /> User-Agent: Internet-Explorer 9.0 |
| Add country  | POST  | POST /restapi/country HTTP 1.1 <br /> Host: my.site.com <br /> User-Agent: Internet-Explorer 9.0 <br /> Content-Type: application/json <br /> Content-Length: 50 <br /> {"Name":"Romania", "Description":"Great Country" } |
| Add hotel to country | POST  | POST /restapi/hotel HTTP 1.1 <br /> Host: my.site.com <br /> User-Agent: Internet-Explorer 9.0
Content-Type: application/json <br /> Content-Length: 72 <br /> {"Name":"My Hotel", "Country": "Ukraine", "Description":"Family Hotel" } |
| Delete hotel  | DELETE  | DELETE /restapi/hotel/22 HTTP 1.1 <br /> Host: my.site.com <br /> User-Agent: Internet-Explorer 9.0 |
| Get info about hotel | GET | GET /restapi/hotel/22 HTTP 1.1 <br /> Host: my.site.com <br /> User-Agent: Internet-Explorer 9.0 |
| Update info about hotel  | PUT | PUT /restapi/hotel/23 HTTP 1.1 <br /> Host: my.site.com <br /> User-Agent: Internet-Explorer 9.0
Content-Type: application/json <br /> Content-Length: 76 <br /> {"Name":"Holiday Inn","Country":"Ukraine", "Description":"B&B cheap hotel" } |
