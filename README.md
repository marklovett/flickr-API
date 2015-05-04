# flickr-API
Accessing flickr's public feed using AJAX and the flckr API.

A page on our client’s site cant normally request data from flickr using AJAX, because flickr uses a different server and domain then the client.

To work around this issue we are using JSONP in this app.

In this case, we are linking to a js file on flickr’s server and our browser will allow js to send us all the photo data wrapped in a js file using JSONP(json with padding).



