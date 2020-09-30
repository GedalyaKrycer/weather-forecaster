# hw-6-weather-dashboard
Weather dashboard for major cities

### [View Deployed Site](https://gedalyakrycer.github.io/weather-forecaster/)


## Goal 
Create a website that uses the [Open Weather API](https://openweathermap.org/api) to display the current weather and a 5 day forecast, based on the location a user inputs. Submitted locations are also to be saved to local storage and displayed in section on the site, pulling up their information at a later time. 

I took the project a step further by re-imaging the layout and design, but still using the fundamental features that were given. 

### Original Mockup That Was Provided 
![Original Mockup](./assets/06-server-side-apis-homework-demo.png)

### New Design
![New Design](./assets/img/weather-dashboard.gif)

## Key Highlights 
* Search input field grows in side, when "focused" on

* Custom Design that is also responsive 

* Most of the result and location results are dynamically being generated by JavaScript

* Weather data is being pulled from the Open Weather API, using 3 different endpoints
    * UV Index
    * Current Weather 
    * 3 Hour / 5 Hour Forecast 

* UV Index changes it's color based on the number that is returned, based on the EPA's rating system. 
    * 0-2 Green (Favorable)
    * 3-5 Yellow (Moderate)
    * 6-7 Orange (High)
    * 8+ Red (Severe)


## Future Additions
* Adding a "Clear" **x** button to remove individual saved locations 
* Adding a "Clear All" button to remove all locations
* Refining layout for the 5 Day Forecast columns, so they wrap at a larger breakpoint 
* Adding in the local storage feature
* Running HTML, CSS, JS through validators
* Fixing the 5 Day Weather Forecast Dates to be Unique. (Ordinal UNIX API data being pulled is unique, but when running through a converter function, it breaks.)
