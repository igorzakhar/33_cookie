# Frontend for SPA «ПомойАвто»

It is a frontend for single page application. Reach JavaScript is present.

# Deploy on localhost

Example of frontend launch on Linux, Python 3.5:

```bash
cd static/
python3 -m http.server 9000
```

Open page [localhost:9000](localhost:9000) in browser.

# Deploy on production server

If you make a request to app, you will notice a header being returned:  


_**Access-Control-Allowed-Origins:** Custom header with list of allowed origins: https&#58;//33_cookie.devman.org https&#58;//33_cookie.dev_  

The Access-Control-Allow-Origin header determines which origins are allowed to access server resources over [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS).  

App has to be deployed one of the following domains:  
- https&#58;//33_cookie.devman.org
- https&#58;//33_cookie.dev

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
