<!-- markdownlint-disable MD033 -->

# Shipping Projection

Allows users the ability to analyze how actual shipping is trending against forecasted shipping for a given time.

![Image](../assets/img/shipping-projection.png)

## Slicers

<img src="../assets/img/shipping-projection-slicers.png" width="300" height="280" />

* Date
  * Allows users the ability to select a date range
* Country (Multiple Selection)
  * Will filter the data to only show transactions for the selected countries
* Currency (Multiple Selection)
  * If selected, will filter the data to show only the transactions for the selected currency

## Totals

<img src="../assets/img/shipping-projection-totals.png" width="500" height="71" />

* Booked
  * Dollars = Shipped Dollars + Balance to Ship Dollars
  * Units = Shipped Units + Balance to Ship Units
* Booked Forecast
  * Dollars = The Forecast Dollars manually entered or uploaded to the Sales Forecast screen in Fashion Web App
  * Units = The Forecast Units manually entered or uploaded to the Sales Forecast screen in Fashion Web App
* Shipped
  * Dollars = Sum of Shipped Dollars on Invoices where AR Type Code = 01 (Invoices)
  * Units = Sum of Shipped Units on Invoices where AR Type Code = 01 (Invoices)
* Shipped Forecast
  * Dollars = Open Orders (Including BTS) $ + Shipped $
  * Units = Open Orders (Including BTS) Units + Shipped Units

## Currency

<img src="../assets/img/shipping-projection-currency.png" width="200" height="35" />

Indicates whether the data shown is in Home or Local Currency, along with the exchange rate stored in the system.

## Forecast vs. Actual Booking

Analyze the Booked Dollars and Units against Forecast Dollars and Units by month. Hovering over a bar will show the Actual Dollars, Actual Units, Forecast Dollars, Forecast Units for the month. Selecting a bar will focus the data to that month.

<img src="../assets/img/shipping-projection-forecast-vs-actual-booking.png" width="800" height="199" />

## Forecast vs. Actual Shipping

Analyze the Shipping Dollars and Units against Forecast Dollars and Units by month. Hovering over a bar will show the Actual Dollars, Actual Units, Forecast Dollars, Forecast Units for the month. Selecting a bar will focus the data to that month.

<img src="../assets/img/shipping-projection-forecast-vs-actual-shipping.png" width="800" height="213" />

## Total Shipped $ by Customer Type

Hovering over a bar will show the Actual $, Forecast $ and % to Forecast for that Customer Type.

<img src="../assets/img/shipping-projection-total-shipped-by-customer-type.png" width="300" height="215" />

## Total Shipped $ by Season

Hovering over a bar will the Actual $, Forecast $ and % to Forecast for that Season.

<img src="../assets/img/shipping-projection-total-shipped-by-season.png" width="300" height="181" />

> **Notes**:
>
> * The forecast date is based on the start delivery date.
> * All dollar amounts are net, not gross.
