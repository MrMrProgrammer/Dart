# Anonymous Functions

```dart
const fruits = ['Apple', 'Mango', 'Banana', 'orange'];

fruits.forEach((fruit) {
  print(fruit);
});
```

```dart
var cube = (int number) {
  return number * number * number;
};

print('the cube of 2 is ${cube(2)}');
```