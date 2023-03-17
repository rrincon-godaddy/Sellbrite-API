---
title: "DateTime Format"
slug: "datetime-format"
excerpt: "Information regarding date-time related values in the Sellbrite API"
hidden: false
createdAt: "2017-02-01T00:59:08.986Z"
updatedAt: "2020-05-20T18:03:00.589Z"
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

Sellbrite uses the ISO 8601 time format for all datetime values. Datetime stamps that are submitted to and returned from the API will be in this format. For example:
[block:code]
{
  "codes": [
    {
      "code": "min_ordered_at: \"2017-01-06T22:28:42Z\"",
      "language": "text"
    }
  ]
}
[/block]
