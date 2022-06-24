# Debugging

## Something is not showing up

First, go into the Client Debug page in OpenLoop. Then, press the Delete Cache button. After that, new OpenLoop assets like pages will show up. OpenLoop caches pages/assets to help the load of the WSGI server.

## PWA is not working

First, go into the Client Debug page in OpenLoop. Check to see if "PWA Compatible" is set to true. If it is true, make sure you have a compatible web browser, browsers like Firefox cache but do not have the ability to create a separate app. If set to false, make sure you are using HTTPS with a service like NGINX and have HTTPS strictly on.

## ERR\_FAILD on a page.

Some OpenLoop pages are not cached for stricter security, like the Client Debug or Authentication pages.

## Heroku Issues

Heroku's free tier limits requests and hibernates OpenLoop. It can take around 5-15 seconds depending on your MongoDB server to load the OpenLoop WSGI server.
