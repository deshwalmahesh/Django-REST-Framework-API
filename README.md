# DRF-API
This is one the 3 projects in Front-API-Admin Series. It exposes API endpoints so that APIs can be consumed by applications


This app produces API for users from 2 methods.

___________________________________________________________

1. SImple Django API :->  These are just simple Json Objects provided by the end points via the models. Nothing fancy nothing complicated.
Anyone can access the APIs who has access to the endpoint.


2 Django-REST-Framework :-> These API use the same model that simple Django API do in this project but the process is protected and
complicated. Not everyone can use the the APIs. Some endpoints are deliberately left open while others can be accessed by the registered
users. A couple of endpoints are used by the Admin only.

Tokens are given to the USers. Token mechanish is automated by the rest-auth library. 

For the Cross Domain Problems, Django-CORS-headers is used in this project to test the API on a different domain and port.
