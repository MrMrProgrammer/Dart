# Properties and Methods in String

```dart
String allNames = 'iman,reza,farshad';

List<String> listNames = allNames.split(',');

print(listNames); // ---> [iman, reza, farshad]
```

```dart
String text = 'i love dart and flutter';

print(text.substring(16));   // ---> flutter
print(text.substring(7,11)); // ---> dart
```

```dart
String input = 'Flutter';
print(input.split('').reversed.join()); // ---> rettulF
```

```dart
String text = 'hello flutter';

print('capitalized first letter of string : ${text[0].toUpperCase()}${text.substring(1)}'); // ---> capitalized first letter of string : Hello flutter
```