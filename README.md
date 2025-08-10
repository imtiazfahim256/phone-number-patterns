# Phone Patterns

A curated collection of regular expressions and metadata for validating international phone numbers by country.

## Features

- Regex patterns for mobile numbers (and optionally landlines) from 200+ countries  
- Includes country name, ISO code, emoji flag, dialing codes, and flag images  
- Easy to use for front-end and back-end phone validation  
- Helps build accurate and user-friendly phone input validation  

## Usage

Use the provided regex patterns to validate phone numbers based on the selected country in your application.

```js
const pattern = phonePatterns['BD'].pattern; // Example for Bangladesh
const isValid = new RegExp(`^${pattern}$`).test('1634481182');
