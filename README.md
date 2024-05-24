# phone-number-prefixes
A collaborative repository for managing phone number prefixes by gateway and country.

This repository is dedicated to managing and organizing phone number prefixes by gateway and country. Our goal is to create a comprehensive and accurate list that can be used for various telecommunication and data processing needs.

## Repository Structure

- **prefixes.json**: This JSON file contains the list of phone number prefixes, organized by country and gateway.

## JSON Structure

The `prefixes.json` file follows this structure:

```json
{
  "countries": [
    {
      "country": "Country Name",
      "gateways": [
        {
          "name": "Gateway Name",
          "prefixes": ["+123", "+456"]
        }
      ]
    }
  ]
}
