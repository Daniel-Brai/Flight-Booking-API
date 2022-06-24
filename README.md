# Flight-Booking-API
Zuri-Node-JS-Task-5: A simple flight booking API built with express utilizing for routing and JSON for strorage

## How to use
1. Open up the terminal of your choice, run `npm i` to install the necessary dependencies
2. After the installing the dependencies, run `npm run dev` to start up i development mode
3. You can proceed querying the API with postman, insomnia or thunder client

### Format for data types in the body
An id is automatically generated
- title: String
- time: String
- price: Number
- date: String ; but it should be a valid date time string e.g "June 24, 2022" or "2022-05-24"

An example of your result should be in format: 
`[
  {
    "id":"l4sgened",
    "title":"Flight to Kaduna",
    "time":"3pm",
    "price":63000,
    "date":"Sun Jul 03 2022"
  }
 ]`
