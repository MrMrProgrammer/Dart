### Runes

```dart
String value = 'K';

print(value.runes); // ---> (75)
```
#### The `runes` property returns an iterable of the Unicode code points for each character in the string.

### runtimeType
```dart
var num = 10;
print(num.runtimeType); // ---> int
```

### is
```dart
var num = 10;
print(num is int);  // ---> true
print(num is! int); // ---> false
```

### Static Data Type
```dart
var myVariable = 50;  // 
myVariable = 'hello'; // ---> Error!
print(myVariable);
```

### Dynamic Data Type
```dart
dynamic myVariable = 50;
myVariable = 'iman';
print(myVariable); // ---> iman
```

### Comment
```dart
// this is comment

/* this is multiline comment
foo
bar
*/

/// comment for docs
```
