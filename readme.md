## What is CCJS?

CCJS is a simple, no-fluff library adopted from [CardJS](https://cardjs.co.uk/).
It only support Credit Card input field, no CVV, no expiry date, purely just to
transform a text field into a credit-card field with proper spacing.

![ccjs in action](https://cloud.githubusercontent.com/assets/166730/11923261/851ca5c4-a7d3-11e5-8b94-02ccc302d661.png)

## Installation

Can simply download the files required from this repo, those files are:

1. The PNG
2. The CSS
3. The JavaScript

Or use bower:

```
bower install ccjs
```

## Usage

Import the CSS and Javascript accordingly, to your HTML document. And then
invoke the following code:

```javascript
$(".my-credit-card-field").makeCreditCardField()
```

Probably using jQuery:

```javascript
$(document).ready(function() {
  $(".my-credit-card-field").makeCreditCardField()
})
```

## Cards for you to try

| Number              | Card Type               |
|---------------------|-------------------------|
| 4111 1111 1111 1118 | Visa                    |
| 5555 5555 5555 4444 | MasterCard              |
| 3782 822463 10005   | American Express (AMEX) |
| 6011 1111 1111 1117 | Discover                |
| 3056 930902 5904    | Diners Club             |
| 3530 1113 3330 0000 | JCB                     |

