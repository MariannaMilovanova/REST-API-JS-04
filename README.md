REST API Small Task

| Description  | Method | HTTP Request|
| ------------- | ------------- |------------- |
| Get list of countries  | GET  |GET /restapi/country HTTP 1.1 \n\r Host: my.site.com \n\r User-Agent: Internet-Explorer 9.0 |
| Get list of hotels in country  | GET  | GET /restapi/hotel/country/ukraine HTTP 1.1
Host: my.site.com
User-Agent: Internet-Explorer 9.0 |
| Add country  | POST  | POST /restapi/country HTTP 1.1
Host: my.site.com
User-Agent: Internet-Explorer 9.0
Content-Type: application/json
Content-Length: 50
{"Name":"Romania", "Description":"Great Country" } |
| Add hotel to country | POST  | POST /restapi/hotel HTTP 1.1
Host: my.site.com
User-Agent: Internet-Explorer 9.0
Content-Type: application/json
Content-Length: 72

{"Name":"My Hotel", "Country": "Ukraine", "Description":"Family Hotel" } |
| Delete hotel  | DELETE  | DELETE /restapi/hotel/22 HTTP 1.1
Host: my.site.com
User-Agent: Internet-Explorer 9.0 |
| Get info about hotel | GET | GET /restapi/hotel/22 HTTP 1.1
Host: my.site.com
User-Agent: Internet-Explorer 9.0 |
| Update info about hotel  | PUT | PUT /restapi/hotel/23 HTTP 1.1
Host: my.site.com
User-Agent: Internet-Explorer 9.0
Content-Type: application/json
Content-Length: 76

{"Name":"Holiday Inn","Country":"Ukraine", "Description":"B&B cheap hotel" } |
