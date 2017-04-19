# App Engine Standard & Google Cloud Endpoints Frameworks & Java

This sample demonstrates how to use Google Cloud Endpoints Frameworks using
Java on App Engine Standard.

To send a request to the API, from a command line, invoke the following `cURL`
command:

     curl \
         -H "Content-Type: application/json" \
         -X POST \
         -d '{"message":"echo"}' \
         https://cloud-end-point.appspot.com/_ah/api/echo/v1/echo

You will get a 200 response with the following data:

    {
     "message": "echo"
    }
