# django_basic_auth
Basic django authentication with REST api

# Obtain access and refresh token by only POST requests using cURL or HTTPie
`http post http://127.0.0.1:8000/api/token/ username=nishant password=123`

# Access Token usage
`http http://127.0.0.1:8000/hello/ "Authorization: Bearer eyJ0eXAiOuJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ0b2tlbl90eXBlIjoiYWNjZXNzIiwiZXhwIjoxNTQ1MjI0MjAwLCJqdGkiOiJlMGQxZDY2MjE5ODc0ZTY3OWY0NjM0ZWU2NTQ2YTIwMCIsInVzZXJfaWQiOjF9.9eHat3CvRQYnb5EdcgYFzUyMobXzxlAVh_IAgqyvzCE"`

# Refresh token usage (Expires in five minutes)
`http post http://127.0.0.1:8000/api/token/refresh/ refresh=eyJ0eXAiOuJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ0b2tlbl90eXBlIjoicmVmcmVzaCIsImV4cCI6MTU0NTMwODIyMiwianRpIjoiNzAyOGFlNjc0ZTdjNDZlMDlmMzUwYjg3MjU1NGUxODQiLCJ1c2VyX2lkIjoxfQ.Md8AO3dDrQBvWYWeZsd_A1J39z6b6HEwWIUZ7ilOiPE`

![screenshot](https://github.com/nishantc7/django_basic_auth\screenshot.png "Screenshot")

