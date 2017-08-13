# weather-app
Command line app to get current weather of a location.

It uses location API of google maps to get coordinates of a given location, and then uses the darknet API to get weather information of the place corresponding to those coordinates.

This is a very basic app that I used while learning node.js promises. This app uses the `npm` module `axios`, which supports promises.  
Earlier, I'd made a version of this app using `request`, which uses callbacks (instead of promises). Later, I wrapped the request function in a Promise object to understand how to make Promises work with modules that don't directly support it. 

## Running the app
First, clone into the repository using the `git clone` command.  
Navigate to the downloaded folder using `cd`.  
Run `npm install` on the terminal, and you're ready to go.

Use the help flag to know more about the commands.  
`node app-promise.js --help`

There is only one flag that is required by this app: -a or --address.  

`node app-promise.js -a 'some address'`  
`node app-promise.js --address 'some address'`
