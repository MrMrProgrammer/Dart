# Lists

### ‍`map` Method in Lists

```dart
List<int> list = [1, 2, 3, 4, 5, 6, 7, 8, 9];
list.forEach((element) => print(element));

var doubleList = list.map((e) => e * 2);
print(doubleList);
```

### Using ‍`conditional` statements in `lists`
```dart
bool sad = true;
var cart = ['milk', 'coffee', if (sad) 'coke'];
print(cart); // ---> [milk, coffee, coke]
```

### Use search query (`where`) in lists
```dart
List<int> numbers = [2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16];

List<int> even = numbers.where((number) => number.isEven).toList();
print(even); // ---> [2, 4, 6, 8, 10, 12, 14, 16]

List<int> odd = numbers.where((number) => number.isOdd).toList();
print(odd); // ---> [3, 5, 7, 9, 11, 13, 15]
```

### `clear()` method
```dart
odd.clear();
print(odd); // ---> []
```