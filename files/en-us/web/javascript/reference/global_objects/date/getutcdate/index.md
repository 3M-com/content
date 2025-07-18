---
title: Date.prototype.getUTCDate()
short-title: getUTCDate()
slug: Web/JavaScript/Reference/Global_Objects/Date/getUTCDate
page-type: javascript-instance-method
browser-compat: javascript.builtins.Date.getUTCDate
sidebar: jsref
---

The **`getUTCDate()`** method of {{jsxref("Date")}} instances returns the day of the month for this date according to universal time.

{{InteractiveExample("JavaScript Demo: Date.prototype.getUTCDate()")}}

```js interactive-example
const date1 = new Date("August 19, 1975 23:15:30 GMT+11:00");
const date2 = new Date("August 19, 1975 23:15:30 GMT-11:00");

console.log(date1.getUTCDate());
// Expected output: 19

console.log(date2.getUTCDate());
// Expected output: 20
```

## Syntax

```js-nolint
getUTCDate()
```

### Parameters

None.

### Return value

An integer, between 1 and 31, representing day of month for the given date according to universal time. Returns `NaN` if the date is [invalid](/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date#the_epoch_timestamps_and_invalid_date).

## Examples

### Using getUTCDate()

The following example assigns the day of month of the current date to the variable `dayOfMonth`.

```js
const today = new Date();
const dayOfMonth = today.getUTCDate();
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{jsxref("Date.prototype.getUTCDay()")}}
- {{jsxref("Date.prototype.getDay()")}}
- {{jsxref("Date.prototype.setUTCDate()")}}
