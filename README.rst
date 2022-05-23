Basic Github App
----------------------

A starter webservice for building a GitHub App using gidgethub (v4.1.0+), aiohttp, and
deployment to Railway.app.

Railway.app Setup
------------


|Deploy|

.. |Deploy| image:: https://railway.app/button.svg
   :target: https://railway.app//deploy?template=https://github.com/CodeWhiteWeb/First-Github-app


Add the following config vars in Railway.app.

``GH_SECRET``: The secret key from your GitHub App

``GH_APP_ID``: The ID of your GitHub App

``GH_PRIVATE_KEY``: The private key of your GitHub App. It looks like:

```

-----BEGIN RSA PRIVATE KEY-----
...somereallylongtext...
-----END RSA PRIVATE KEY-----

```
