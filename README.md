# CORS policy demonstration

This repo includes an API Proxy and a web app that can be used to demonstrate
and exercise the CORS policy in Apigee.


## Instructions

1. deploy the webapp to your web host of choice. You can also host it locally (via localhost).

2. import and deploy the apiproxy to your Apigee org/environment.

2. start a trace on the proxy.

3. open a browser tab to the URL on which the web app is listening.

4. In the browser, Open developer tools, and in that panel, go to the network pane.

5. Configure the web form to point to the Apigee API endpoint. Fill in the other parameters, like headers and verb. Send the request.

6. observe the results.
