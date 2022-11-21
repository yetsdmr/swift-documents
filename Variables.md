## Variables 📖
The variable corresponds to holding data in programming languages.

## Usage 🔨

### String and Integer
```swift
// Variable Type is String
var name = "Emre"
// Variable Type is Integer
var number = 15
print(name) // Emre
print(number) // 15
// If you wanna change the value, you don't need "var" tag
name = "Taşdemir"
number = 9
// Same variables but value was changed
print(name) // Taşdemir
print(number) // 9 
```

### Multiline String, Double and Boolean
```swift
// Variable Type is Multiline String
var multilineText = """
I'm learning
Swift and UIKit
And This variable is
Multiline string
"""
// Variable Type is Double
var doubleNum = 13.4789 // Dot provide this
// Variable Type is Boolean
var learn = true
```

### String Interpolation
```swift
// How to use variables in string. So String interpolation.
var myScore = 89
var scoreStr = "My score is : \(myScore)" // My score is : 89
```

### Constants
```swift
// If you never want your variable to change. Use it
let tryChange = "Swift"
tryChange = "I have tried" // You should see a warning that the constant is immutable. So you can't change.
```

### Type annotations
```swift
// If you want to predetermine the variable type
var number : Int = 15
var name : String = "Emre" 
var myBoolean : Bool = true
var myDouble : Double = 13.48
// This avoids misuse of the variable
number = "Taşdemir" // You can't do this. Because variable type is an integer.
number = 10 // But you can do this
```

## Tips 🤔💭

### Integer
```swift
// If your Integer value was big
var number = 1_000_000 // Use this writing style. More readable style than normal writing style for integer 
```
### Multiline String
```swift
// If you want a smooth formatting for multiline string
var longText = """
This is good \
smooth formatting \
for multiline string
"""
```

### Constants

```swift
var anyNumber = 10 // Xcode will warn you to convert the variable to constant. 
let anyNumber = 10 // If you're not going to change the variable at all, use this line.
print(anyNumber)
```
