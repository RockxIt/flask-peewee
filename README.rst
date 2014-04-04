flask-peewee with some customization
============

custom routes in api
------------

You can specify custom routes for the api, and use the same model multiple times, which can be useful if you output custom data using the prepare_data() hook.

Usage: api.register(Model, provider=RestResource, route='myroute')
url => /api/myroute
