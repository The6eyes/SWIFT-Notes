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

Arrays also have modifiers 

