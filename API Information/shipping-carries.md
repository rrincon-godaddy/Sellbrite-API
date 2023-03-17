---
title: "Shipping Carriers and Methods"
slug: "shipping-carries"
hidden: false
createdAt: "2017-02-16T21:16:53.876Z"
updatedAt: "2017-05-30T22:49:24.985Z"
---
Most channels do not require and do not accept carrier specific shipping methods.  One exception is Sears, which requires a specific shipping method name that is compatible with the provided carrier name.  Below is a list of accepted shipping methods that you can provide when creating a shipment for a specific carrier in Sellbrite.  Sellbrite will use this in the api call to the channel if it is required. 
[block:api-header]
{
  "title": "Examples"
}
[/block]
shipping carrier: "USPS"
shipping method: "Priority Mail"

shipping carrier: "USPS"
shipping method: "Priority Mail International"

shipping carrier: "DHL eCommerce"
shipping method: "Domestic Express Doc"
[block:code]
{
  "codes": [
    {
      "code": "Priority Mail\nPriority Mail Express\nFirst Class Mail\nParcel Select\nMedia Mail\nPriority Mail International\nPriority Mail Express International\nFirst Class Mail International",
      "language": "text",
      "name": "USPS"
    }
  ]
}
[/block]

[block:code]
{
  "codes": [
    {
      "code": "Ground\nHome Delivery\nSmartPost\n2 Day\n2 Day A.M.\nExpress Saver\nStandard Overnight\nPriority Overnight\nFirst Overnight\nInternational Economy\nInternational Priority\nInternational First\nEurope First International Priority",
      "language": "text",
      "name": "FedEx"
    }
  ]
}
[/block]

[block:code]
{
  "codes": [
    {
      "code": "Standard\nGround\nSaver\nThree-Day Select\nSecond Day Air\nSecond Day Air A.M.\nNext Day Air\nNext Day Air Saver\nNext Day Air Early A.M.\nMail Innovations\nSurePost\nSurePost Lightweight\nExpress\nExpress Plus\nExpedited",
      "language": "text",
      "name": "UPS"
    }
  ]
}
[/block]

[block:code]
{
  "codes": [
    {
      "code": "Express Post\nParcel Post",
      "language": "text",
      "name": "Australia Post"
    }
  ]
}
[/block]

[block:code]
{
  "codes": [
    {
      "code": "Regular Parcel\nExpedited Parcel\nPriority\nXpresspost\nXpresspost International\nXpresspost USA\nExpedited Parcel USA\nPacket USA\nSmall Packet USA Air\nTracked Packet International\nSmall Package International Air",
      "language": "text",
      "name": "Canada Post"
    }
  ]
}
[/block]

[block:code]
{
  "codes": [
    {
      "code": "Postkarte\nStandardbrief\nKompaktbrief\nGrossbrief\nMaxibrief\nMaxibrief Plus",
      "language": "text",
      "name": "Deutsche Post"
    }
  ]
}
[/block]

[block:code]
{
  "codes": [
    {
      "code": "Domestic Express Doc\nEconomy Select Doc\nExpress Worldwide Nondoc\nExpress Worldwide Doc\nWorldwide\nExpress Worldwide EU Doc\nBreak Bulk Express Doc\nExpress 9:00 NonDoc\nEconomy Select NonDoc\nBreak Bulk Economy Doc\nExpress 9:00 Doc\nExpress 10:30 Doc\nExpress 10:30 NonDoc\nExpress 12:00 Doc\nEuropack NonDoc\nExpress Envelope Doc\nExpress 12:00 NonDoc\nExpress Worldwide (B2C) Doc\nExpress Worldwide (B2C) NonDoc\nMedical Express\nExpress Easy NonDoc",
      "language": "text",
      "name": "DHL Express"
    }
  ]
}
[/block]

[block:code]
{
  "codes": [
    {
      "code": "First Class Expedited\nPriority Expedited\nBPM Ground\nBPM Expedited\nMarketing Parcel Ground\nMarketing Parcel Expedited\nParcel Plus Ground\nParcel Plus Expedited\nParcel Plus Expedited Max\nParcels Ground Expedited\nParcels Expedited\nParcels Expedited Max\nGround\nExpedited (for Flats)\nLight (for EZ Return)\nPlus (for EZ Return)",
      "language": "text",
      "name": "DHL eCommerce"
    }
  ]
}
[/block]

[block:code]
{
  "codes": [
    {
      "code": "Routed Delivery",
      "language": "text",
      "name": "Lasership"
    }
  ]
}
[/block]

[block:code]
{
  "codes": [
    {
      "code": "Ground\nSunrise Gold\nSunrise",
      "language": "text",
      "name": "OnTrac"
    }
  ]
}
[/block]

[block:code]
{
  "codes": [
    {
      "code": "1st Class\nSigned For 1st Class\n2nd Class\nSigned For 2nd Class\nSpecial Delivery Guaranteed by 9am\nSpecial Delivery Guaranteed by 1pm",
      "language": "text",
      "name": "Royal Mail"
    }
  ]
}
[/block]
