# Weather App

This is a simple weather app using Angular with Rapid API's Open Weather Map API

## Techologies Used
 1. HTML5
 2. LESS
 3. TypeScript
 4. Angular v15.1.6
 6. Node.js v18.14.0
 7. [Open Weather Map API](https://rapidapi.com/worldapi/api/open-weather13/)

## Instructions
In order to run this machine locally, you would need to create an account on Rapid API's website in order to use their API key.
 1. Create an account on Rapid API (https://rapidapi.com)
 2. Download this repository
 3. Open the repository in your machine's terminal and run this Angular CLI command - `ng g environments`. This will create an environments folder to store the API key
 4. Inside *environment.development.ts*, copy and paste the following code:
    
	    export const environment  = {
		    production: false,
		    weatherApiBaseUrl:'https://open-weather13.p.rapidapi.com',
		    XRapidAPIHostName: 'X-RapidAPI-Host',
		    XRapidAPIHostValue: 'open-weather13.p.rapidapi.com',
		    XRapidAPIKeyName: 'X-RapidAPI-Key',
		    XRapidAPIKeyValue: 'SECRET_API_KEY'
	    };
 
 5. Go to Rapid API's Open Weather API (https://rapidapi.com/worldapi/api/open-weather13/)
 6. Scroll down and copy the X-RapidAPI-Key. This is your API Key. 
 7. Inside *environment.development.ts*, replace **SECRET_API_KEY with the copied API Key**.
 8. Lastly, run this app by using CLI command - `ng serve -o`
