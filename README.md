# CORS policy demonstration

This repo includes an API Proxy and a web app that can be used to demonstrate
and exercise the CORS policy in Apigee.


## Instructions

1. deploy the webapp to your web host of choice. You can also host it locally (via localhost). Or use [the publicly-hosted  webapp](https://dinochiesa.github.io/cors-demonstrator/).

2. import and deploy the apiproxy to your Apigee org/environment.

3. start a trace (aka debugsession) on the proxy.

4. open a browser tab to the URL on which the web app is listening.

5. In the browser, Open developer tools, and in that panel, select the network pane.

6. Configure the web form to point to the Apigee API endpoint.

7. Fill in the other parameters, like headers and verb, as you desire. Send the request.

8. observe the results.

9. Repeat Step 7 and 8 as desired for other values.
