# burger-api

This is my burger recommendation API.

I am collating a list of nice burgers, mostly in Auckland but some from other places I've been like Tokyo.

I will be starting the list with some burgers in Auckland. If you have any burger recommendations feel free to contribute to my project with pull requests or send me a message!

While still incomplete, the API is available for use [here is the RapidAPI link](https://rapidapi.com/asatenshi/api/burger-rec-api)

# getting started

### clone repo

### install packages

`npm i`

### start server

`npm start`

# Adding Data

```
{
  "id": [id of record | number],
  "name": [name of the burger | string],
  "restaurant": [name of the restaurant | string],
  "web": [url of website/instagram/facebook/etc | string],
  "description": [description of the burger | string],
  "ingredients": [names of ingredients | array of strings],
  "glutenfree": [gluten-free option available | boolean],
  "addresses": [
    {
      "addressid": [id of addresses of stores | string],
      "number": [address number | string],
      "line1": [address line1 | string],
      "line2": [address line1 | string],
      "city": [city name | string],
      "postcode": [postcode | string],
      "country": [country name | string],
    }
  ]
}
```
