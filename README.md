# resonatehq-sample
Resonate HQ sample code


## Running the app
Run the app using
```ssh
npm install
npm run dev
```

## Test the app
Use the following curl command
```ssh
curl --location 'http://localhost:3000/summarize' \
--header 'Content-Type: application/json' \
--data '{"url": "https://httpbin.org/anything"}'
```

The application asynchronously invokes the URL specified and then calls a second function getting the response.
You can use other API calls available on [httpbin](https://httpbin.org/).
