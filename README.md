# AdPage Spotler Purchase Tag

This server tag allows you to send purchase events to Spotler's API.

## Authentication

- **Account ID** - Your Spotler account ID for authentication
- **API Key** - Your Spotler API key for authentication

## Required Fields

### Customer Information

- **Customer Email** - Customer email or SHA256 of the email
- **Order ID** - Order reference of the purchase

### Products

Each product requires:

- **Product ID** - Unique identifier for the product
- **Product Name** - Name of the product
- **Price** - Price of the product
- **Quantity** - Quantity purchased

## Optional Fields

### Customer Details

- **First Name** - Customer's first name
- **Last Name** - Customer's last name
- **User ID** - Your unique identifier for the customer
- **Mobile Advertiser ID** - Mobile advertising identifier
- **Gender** - Customer's gender (M/F/U)
- **Birth Date** - Customer's birth date (YYYY-MM-DD)
- **Phone** - Phone number in E164 format (e.g. +31612345678)

### Location Information

- **Postal Code** - Customer's postal code
- **City** - Customer's city
- **Country** - 2-letter country code (ISO 3166-1 alpha-2)

### Additional Settings

- **Currency** - Currency code (e.g. EUR/USD/GBP)
- **Language** - Language code (ISO 639-1 and ISO 3166-1 alpha-2, e.g. en-US)
- **Newsletter Opt-in** - Newsletter subscription status (yes/no)
- **Total Value** - Total purchase value (overrides calculated value from products)
