---
title: "Shipping Carriers and Methods"
slug: "shipping-carries"
hidden: false
createdAt: "2017-02-16T21:16:53.876Z"
updatedAt: "2017-05-30T22:49:24.985Z"
---
### Menu

[Introduction](introduction)

[Credentials](credentials)

[Authentication](authentication)

[Rate Limits](rate-limits)

[DateTime Format](datetime-format)

[Carrier Names](carrier-names)

[Shipping Carries and Methods](shipping-carries)

---

Most channels do not require and do not accept carrier specific shipping methods.  One exception is Sears, which requires a specific shipping method name that is compatible with the provided carrier name.  Below is a list of accepted shipping methods that you can provide when creating a shipment for a specific carrier in Sellbrite.  Sellbrite will use this in the api call to the channel if it is required. 
[block:api-header]
{
  "title": "Examples"
}
[/block]
shipping carrier: "USPS"
shipping method: "Priority Mail"

<<<<<<< HEAD
<<<<<<< HEAD
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
=======

shipping carrier: "USPS"
shipping method: "Priority Mail International"


shipping carrier: "DHL eCommerce"
shipping method: "Domestic Express Doc"

USPS
```
Priority Mail
Priority Mail Express
First Class Mail
Parcel Select
Media Mail
Priority Mail International
Priority Mail Express International
First Class Mail International
```

FedEx
```
Ground
Home Delivery
SmartPost
2 Day
2 Day A.M.
Express Saver
Standard Overnight
Priority Overnight
First Overnight
International Economy
International Priority
International First
Europe First International Priority
```

UPS
```
Standard
Ground
Saver
Three-Day Select
Second Day Air
Second Day Air A.M.
Next Day Air
Next Day Air Saver
Next Day Air Early A.M.
Mail Innovations
SurePost
SurePost Lightweight
Express
Express Plus
Expedited
```

Australia Post
```
Express Post
Parcel Post
```

Canada Post
```
Regular Parcel
Expedited Parcel
Priority
Xpresspost
Xpresspost International
Xpresspost USA
Expedited Parcel USA
Packet USA
Small Packet USA Air
Tracked Packet International
Small Package International Air
```

Deutsche Post
```
Postkarte
Standardbrief
Kompaktbrief
Grossbrief
Maxibrief
Maxibrief Plus
```

DHL Express
```
Domestic Express Doc
Economy Select Doc
Express Worldwide Nondoc
Express Worldwide Doc
Worldwide
Express Worldwide EU Doc
Break Bulk Express Doc
Express 9:00 NonDoc
Economy Select NonDoc
Break Bulk Economy Doc
Express 9:00 Doc
Express 10:30 Doc
Express 10:30 NonDoc
Express 12:00 Doc
Europack NonDoc
Express Envelope Doc
Express 12:00 NonDoc
Express Worldwide (B2C) Doc
Express Worldwide (B2C) NonDoc
Medical Express
Express Easy NonDoc
```

DHL eCommerce
```
First Class Expedited
Priority Expedited
BPM Ground
BPM Expedited
Marketing Parcel Ground
Marketing Parcel Expedited
Parcel Plus Ground
Parcel Plus Expedited
Parcel Plus Expedited Max
Parcels Ground Expedited
Parcels Expedited
Parcels Expedited Max
Ground
Expedited (for Flats)
Light (for EZ Return)
Plus (for EZ Return)
```

Lasership
```
Routed Delivery
```

OnTrac
```
Ground
Sunrise Gold
Sunrise
```

Royal Mail
```
1st Class
Signed For 1st Class
2nd Class
Signed For 2nd Class
Special Delivery Guaranteed by 9am
Special Delivery Guaranteed by 1pm
```
>>>>>>> parent of 0cf8ece... Update shipping-carries.md

