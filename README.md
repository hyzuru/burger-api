# burger-api

This is my burger recommendation API.

I am collating a list of gourmet burgers I've eaten and would recommend.

I will be starting the list with some burgers in Auckland, maybe Tokyo. If you have any burger recommendations feel free to contribute to my project with pull requests or send me a message!

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
