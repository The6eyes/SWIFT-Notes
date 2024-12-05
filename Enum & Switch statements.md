# Enum

The simplest explantion of what an `Enum` is a group values that are related. To make an `enum` we must use the keyword `enum` and then name it something. Inside the scope is where we have our different cases. 

here is a basic example 

```swift
enum DayofWeek  {
    case monday
    case tuesday
    case wednesday
    case thursday
    case friday
    case saturday
    case sunday
}
```
We can clean up our code by using raw value as an alternative to all of those if statements. We give our raw value a type and in this case it will be string and that will be declared in the name of the enum. Now every case in our direction enum will have a raw value attatched to it.
