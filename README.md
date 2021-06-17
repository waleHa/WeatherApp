

#  Clima

## My Goal:
I used Application Programming Interfaces (APIs) to grab live weather data from the internet. I have made a beautiful, dark-mode enabled weather app. This app checks the weather for the current location based on the GPS data from the iPhone as well as by searching for a city manually. 


## What I learned:
* How to create a dark-mode enabled app.
* How to use vector images as image assets.
* How use the UITextField to get user input. 
* Learn about the delegate pattern.
* Swift protocols and extensions. 
* Swift guard keyword. 
* Swift computed properties.
* Swift closures and completion handlers.
* How to use URLSession to network and make HTTP requests.
* Parse JSON with the native Encodable and Decodable protocols. 
* How to use Grand Central Dispatch to fetch the main thread.
* How to use Core Location to get the current location from the phone GPS. 


### Condition Codes
```
switch conditionID {
        case 200...232:
            return "cloud.bolt"
        case 300...321:
            return "cloud.drizzle"
        case 500...531:
            return "cloud.rain"
        case 600...622:
            return "cloud.snow"
        case 701...781:
            return "cloud.fog"
        case 800:
            return "sun.max"
        case 801...804:
            return "cloud.bolt"
        default:
            return "cloud"
        }
