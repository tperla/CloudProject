# Ice Cream Parlor Management System

This repository contains the source code and documentation for an Ice Cream Parlor Management System. The system aims to provide an efficient platform for ice cream parlor owners to manage their menu and for customers to place delivery orders online.

## Overview

The Ice Cream Parlor Management System is a web-based application developed using ASP.NET MVC framework. It incorporates various functionalities including menu management, order placement, historical analytics, and optional predictive analysis for ice cream consumption.

## Features

### For Ice Cream Shop Owners:
- **Login**: Secure authentication for owners to access management features.
- **Menu Management**: Add, remove, or update ice cream details including name, description, and photo.
- **View Consumption History**: Access past ice cream consumption history within a specified date range.
- **Sales Forecast (Optional)**: Conduct historical analysis and forecast sales for a future date.

### For Customers:
- **Place Order**: Conveniently place delivery orders, selecting up to 5 flavors and providing delivery address.
- **Payment Integration (Bonus)**: Option for customers to pay via PayPal.

### Additional Functionalities:
- **Image Content Analysis**: Ensures validity of menu item images through content analysis.
- **Address Integrity Check**: Validates delivery addresses for accuracy.
- **Weather Data Recording**: Records weather data and holiday status for each delivery order.
- **Historical Data Visualization**: Presentation of historical order data through tables or graphs.
- **Predictive Analysis (Optional)**: Analyze and predict ice cream consumption based on various factors.

## Technology Stack

- ASP.NET MVC (Core 6.0/7.0)
- Gateway API for accessing cloud services
- Entity Framework for relational database management
- Integration with reliable cloud services:
  - Image content analysis: com.imagga
  - Weather data: org.openweathermap
  - Image storage: Firebase Storage
  - Message broker services: Cloudkarafka, Upstash
