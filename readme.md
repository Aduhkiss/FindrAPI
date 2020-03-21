# Findr Web API Documentation

Welcome to the Findr Web API Documentation! These documents will help you figure out how to use our web api for our website.
Hopefully we can help you get started with using our API, and doing cool things with it!

### How to make requests to our API

If you are just starting out with making web requests with our web api, we recommend using the linux curl command to send data
to and from our api. For an example, if I wanted to ask the API to give me information about my user account, I would run:
`curl -H "Authorization: <My API Key>" -d id=1 https://findr.today/api/v1/profile`

This would send a basic web request to the endpoint that handles profiles, and would give the query "id=1" with a header of
"Authorization: <My API Key>". If you wanted to know what this would look like if you wanted to test it out in your browser, that would be:

`https://findr.today/api/v1/profile?id=1`

However this would not work since this doesn't provide a header, with your API token. (Which is required for all requests with our API)

### Chapters

<Insert links to the different chapters here someday>