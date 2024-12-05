# Collection Types 

We use collection types to store lists of data. There are three basic collection types: `arrays` `sets` and `dictionary`

# Arrays 

Definition: Container or list of objects. They start at 0 btw. They also go in order by the order it was inputed.

For example:

We can first establish a few `constants` that are `srings`

```swift
let naruto = "naruto"
let sasuke = "sasuke"
let sakura = "sakura"
```
We can now create an array constant by giving it a name and then adding brackets `[]` and inside those brackets we will start adding our constants.

```swift
let teamSeven = [Naruto, Sasuke, Sakura]
```

We can also call the name of the  `array` and then put a specific number number inside a `[]` Braket to call whatever thing we put inside the array. This is called `subscripting`

For example

```swift
teamSeven[2]
teamSeven[1]
teamSeven[3]
```

We can also use empty arrays but we would have to declare the type first

For example

```swift
var ages: [Int] = []
```
By doing this X code knows that we want an array of ints. So if later you tried to put a different "type" like string or a boolean it wouldnt work because we decalred it to be an array of ints.

Arrays also have modifiers like:
```swift
`.count`
`.first`
`.last`
`.sort()`
`.reverse()`
`.shuffle()`
```
# Dictionary

Definition: A collection type. This collection of items have labels called key: Value pairs. Its just like a real dicionary with the `word:definition`

For example 

```swift
let devices: [String:   String] = [
    "phone": "iPhone X" ,
    "laptop": "2016 MacBook Pro" ,
    "tablet": "2018 iPad Pro"   ,
    "desktop": "2017 iMac Pro"  ,
]
devices["phone"]
```

# Set 

Definition: Very similiar to arrays. They are collections of items that are unordered, they can not have duplicates unlike arrays, and has faster performance due to the hash value requirement.

```swift
var ages2 = [3,8,14,18,24]

var agesSet = Set(ages2)
print(agesSet)

agesSet.insert(909)
agesSet.insert(99)
agesSet.contains(99)

print(agesSet)
```

These are the 3 main collection types.
