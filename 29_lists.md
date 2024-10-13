# Lists
```dart
List<int> ages = [10, 30, 23];

List<String> names = ['iman', 'farshad', 'ali'];

var mixed = [10, 'iman', true, 10.25];
```

```dart
var list = List.filled(5, 0);
print(list); // ---> [0, 0, 0, 0, 0]
```

```dart
var list = [210, 21, 33, 22, 44, 55];

print(list[0]); // ---> 210

print(list.indexOf(44)); // ---> 4

print(list.length); // ---> 6

list[4] = 76;
print(list); // ---> [210, 21, 33, 22, 76, 55]
```

## Methods
### Some Methods in Lists
- first
- last
- isEmpty
- isNotEmpty
- lenght
- reversed
- single

```dart
List<String> drinks = ['water', 'juice', 'milk', 'coke'];
List<int> ages = [];

print(drinks.first);                 // ---> water
print(drinks.last);                  // ---> coke
print(drinks.isEmpty.toString());    // ---> false
print(drinks.isNotEmpty.toString()); // ---> true
print(ages.isEmpty.toString());      // ---> true
print(ages.isNotEmpty.toString());   // ---> false
print(drinks.reversed);              // ---> (coke, milk, juice, water)
```