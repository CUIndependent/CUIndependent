#Swift Specific styles

- Use 4 spaces as the indentation for all swift files. Do not use tabs.
- Do not use semicolons in swift with the exception of `for` statements.
- Use swift's native types as much as possible as opposed to Objective-C NS types.
- Use `let` as much as possible instead of `var`
- Try to use the `for-in` style of `for` loop instead of the `for-condition-increment` style. (see example below)

**for-in (preferred):**
```swift
for _ in 0..<3 {
  println("Hello three times")
}

for (index, person) in enumerate(attendeeList) {
  println("\(person) is at position #\(index)")
}
```

**for-condition-increment (not preferred):**
```swift
for var i = 0; i < 3; i++ {
  println("Hello three times")
}

for var i = 0; i < attendeeList.count; i++ {
  let person = attendeeList[i]
  println("\(person) is at position #\(i)")
}
```
