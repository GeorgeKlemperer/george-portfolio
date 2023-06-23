# httpProject: The Orbituaries
A project built for practicing interacting with public APIs. Enter a date and a news category on the website to generate an image of NASA's astrology picture of the day (APOD) for that day overlayed with the Guardian's main headline for that day and news genre. The APIs utlized in the website are NASA's apod API, The Guardian API, and Unsplash.

All Founders and Coders projects are collaborative between two people. My partner for this project was Isobel Butler.

View web page here: https://georgeklemperer.github.io/theOrbituaries/.

## 1. Write code that executes asynchronously
<img width="100%" alt="image" src="https://github.com/GeorgeKlemperer/george-portfolio/assets/124908931/daf2255c-4b15-4b5b-a360-937cb0f88ef6">
One example of asynchronous code used in the website where we fetch the APOD HD url from NASA's APOD API. Fetch is used to generate a promise and .then() and .catch() methods are used to schedule callback functions. Similar asynchronous code was used to fetch from the Guardian's and Unsplash's APIs. 

## 2. Access DOM nodes using a variety of selectors
<img width="882" alt="image" src="https://github.com/GeorgeKlemperer/george-portfolio/assets/124908931/3afe9e4f-422c-44fa-86bf-e521826aaddc">


A vareity of DOM nodes were accessed using a variety of selectors. In the above code in point 1 the APOD is inserted as the background imgae for an element. In the below code a different element has a Guardian headline and URL link inserted into it.

<img width="100%" alt="image" src="https://github.com/GeorgeKlemperer/george-portfolio/assets/124908931/cd96f96a-aa24-4f4e-8f28-ff29901dc4b8">

## 3. Display a loading indicator during an API fetch
<img width="100%" alt="image" src="https://github.com/GeorgeKlemperer/george-portfolio/assets/124908931/df83f090-6472-4967-b725-2fcc2ef2304b">

A loading gif is displayed while the submitted queries are fetched.


## 4. Incorporate error handling

<img width="100%" alt="image" src="https://github.com/GeorgeKlemperer/george-portfolio/assets/124908931/29306196-a4ee-4ebf-8f7e-05ed4cc15a4c">

In the event there is no APOD for the date selected (or the APOD is not a picture, as it is occasionally a video) an eerror message is displayed to the user and a random space related image is instead fetched from the Unsplash API. If there is no headline for the date and news category selected by the user a different error message is displayed. Both those scenarios are displayed in the above screenshot.

## 5. Debug client side JS in our web browser

## 6. Use console.log() to help us debug our code
