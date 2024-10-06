# data types

Data Types | Keyword |
--- | --- |
Numbers | int , double , num |
String | String |
Booleans | bool |
Lists | List |
Maps | Map |
Sets | Set |
Runes | runes |
Null | null |


## toStringAsFixed() ---> round
```dart
double prize = 1250.2233554466;
print(prize.toStringAsFixed(2));  // ---> 1250.22
print(prize.toStringAsFixed(4));  // ---> 1250.2234
```

## Show Variable In String
```dart
String name = 'dart';
String url = 'toplearn.com';
print('name is $name and our website is $url');
```

## Multi Line Text
```dart
String multiLineText = '''
This is multi line text
with 3 single quote
this is toplearn
''';

print('multiline text $multiLineText');
```


## Special Characters
```
\n ---> newline
\t ---> tab
```

## Raw String
```dart
num num1 = 10;
print('value with out raw string \t $num1');
String withRawString = r"value is \t $num1";
print('value with raw string $withRawString');
```
