# Type Conversion

### convert String to int
```dart
String strValue = '125';
int intValue = int.parse(strValue);
print('type of intValue is ${intValue.runtimeType}'); ---> int
```


### convert String to double
```dart
String strValue = "10.25";
double doubleValue = double.parse(strValue);
print('type of doubleValue is ${doubleValue.runtimeType}'); ---> double
```

### convert int to String
```dart
int one = 1;
String oneInString = one.toString();
print('one after convert to string ${oneInString.runtimeType}'); ---> String
```


### convert double to int
```dart
double num1 = 10.02;
int num2 = num1.toInt();
print('the value of num2 is $num2 its type is ${num2.runtimeType}'); ---> int
```