# Problem 1

Given a total due and an array representing the amount of change in your pocket, determine whether you are able 
to pay for the item. Change will always be represented in the following order: quarters, dimes, nickels, pennies.

```go
isChangeEnough([2, 100, 0, 0], 14.11) // false

isChangeEnough([0, 0, 20, 5], 0.75) // true

isChangeEnough([30, 40, 20, 5], 12.55) // true

isChangeEnough([10, 0, 0, 50], 3.85) // false

isChangeEnough([1, 0, 5, 219], 19.99) // false
```

Notes 
- **quarter**: 25 cents / $0.25 
- **dime**: 10 cents / $0.10 
- **nickel**: 5 cents / $0.05 
- **penny**: 1 cent / $0.01
