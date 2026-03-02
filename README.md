# Functions in JavaScript

A collection of utility functions for performing common budget-related calculations.

## Overview

This project provides a set of reusable JavaScript functions for numeric calculations, string manipulation, and data validation. The functions are fully tested and ready for integration into budget management applications.

## Requirements

- Node.js 12.0 or higher
- npm

## Installation

```bash
git clone https://github.com/learn-co-curriculum/phase-0-js-functions-lab.git
cd phase-0-js-functions-lab
npm install
```

## API Reference

### `calculateTax(amount)`

Calculates a 10% tax on a monetary amount.

```javascript
calculateTax(100) // Returns: 10
```

**Parameters:**
- `amount` (number) - the monetary value

**Returns:** (number) - the calculated tax amount

---

### `convertToUpperCase(text)`

Converts a string to uppercase.

```javascript
convertToUpperCase("hello") // Returns: "HELLO"
```

**Parameters:**
- `text` (string) - the text to convert

**Returns:** (string) - the uppercase string

---

### `findMaximum(num1, num2)`

Returns the larger of two numbers.

```javascript
findMaximum(5, 10) // Returns: 10
```

**Parameters:**
- `num1` (number) - first number
- `num2` (number) - second number

**Returns:** (number) - the maximum value

---

### `isPalindrome(word)`

Checks if a string is a palindrome.

```javascript
isPalindrome("racecar") // Returns: true
isPalindrome("hello")   // Returns: false
```

**Parameters:**
- `word` (string) - the word to check

**Returns:** (boolean) - `true` if palindrome, `false` otherwise

---

### `calculateDiscountedPrice(originalPrice, discountPercentage)`

Calculates the final price after applying a discount.

```javascript
calculateDiscountedPrice(100, 20) // Returns: 80
```

**Parameters:**
- `originalPrice` (number) - the original price
- `discountPercentage` (number) - the discount percentage to apply

**Returns:** (number) - the discounted price

## Testing

Run the full test suite:

```bash
npm test
```

## License

MIT
