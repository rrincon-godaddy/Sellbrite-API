---
title: "Finding your API credentials"
slug: "credentials"
hidden: false
createdAt: "2017-02-06T22:45:06.416Z"
updatedAt: "2018-10-23T22:45:22.829Z"
---
The Sellbrite API is currently only available on certain Sellbrite plans. [Visit our Pricing page](https://www.sellbrite.com/pricing-pro/) to see which plans include API access. 

Once you have been given API access, click on the "Settings" tab in the top navigation of the Sellbrite app.
[block:image]
{
  "images": [
    {
      "image": [
        "image/reference-1.jpg",
        "sidebar_settings.jpg",
        892,
        447,
        "#f0eef2"
      ]
    }
  ]
}
[/block]
Then click on "API" to display your API credentials. 
[block:image]
{
  "images": [
    {
      "image": [
        "image/reference-2.jpg",
        "sellbrite_api_credentials.jpg",
        1051,
        488,
        "#a281c4"
      ]
    }
  ]
}
[/block]
Please take note of both the ```API token``` and ```Secret Key``` as you will use these two values as the username and password respectively when making requests to the Sellbrite API. Here is a cURL example of making a request for all your orders:
[block:code]
{
  "codes": [
    {
      "code": "curl --user auth_token:secret_key \"https://api.sellbrite.com/v1/orders/7777\"",
      "language": "curl"
    }
  ]
}
[/block]
Please see the [reference guides](reference/introduction) for more examples. If you need more support, please send any questions to <mailto:developer@sellbrite.com>
