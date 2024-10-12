# List

```dart
List<String> names = ['iman', 'farshad', 'ali', 'reza'];

print('values of names is $names'); // ---> ['iman', 'farshad', 'ali', 'reza']
print('values of names[0] is ${names[0]}'); // index 0 ---> iman
print('values of names[1] is ${names[1]}'); // index 1 ---> farshad
print('values of names[2] is ${names[2]}'); // index 2 ---> ali
print('values of names[3] is ${names[3]}'); // index 3 ---> reza


List<int> numbers = [1, 2, 3, 4, 5, 6];

int len = numbers.length; // ---> 6
int lenNames = names.length; // ---> 4
print('the len of numbers is $len');
print('the len of names is $lenNames');
```

# Sets
```dart
Set<String> weekday = {'sun', 'mon', 'tue', 'wed', 'thu', 'fri', 'sat','fri'};
```

# Maps
```dart
Map<String, String> myDetails = {
    'name': 'hamid',
    'age': '39',
    'nationality': 'iranian'
};
```