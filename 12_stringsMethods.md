# Properties and Methods in String

```dart
String str = 'Toplearn';

print(str.codeUnits);  // ---> [84, 111, 112, 108, 101, 97, 114, 110]
print(str.isEmpty);    // ---> false
print(str.isNotEmpty); // ---> true
print(str.length);     // ---> 8
```

```dart
String city1 = 'Tehran';
String city2 = 'MashHad';

print(city1.toUpperCase()); // ---> TEHRAN
print(city2.toUpperCase()); // ---> MASHHAD
print(city1.toLowerCase()); // ---> tehran
print(city2.toLowerCase()); // ---> mashhad
```

```dart
String city1 = ' TEHRAN';
String city2 = 'MASHHAD ';
String city3 = 'New Delhi';

print(city1.trim());      // ---> TEHRAN
print(city2.trim());      // ---> MASHHAD
print(city3.trim());      // ---> New Delhi
print(city1.trimLeft());  // ---> TEHRAN
print(city2.trimRight()); // ---> MASHHAD
```

```dart
String item1 = 'Apple';
String item2 = 'Ant';
String item3 = 'Toplearn';

print(item1.compareTo(item2)); // ---> 1
print(item1.compareTo(item3)); // ---> -1
print(item2.compareTo(item3)); // ---> -1
```

```dart
String text = 'i am a good boy and i like milk . doctor says milk is good for health';
String newText = text.replaceAll('milk', 'water');

print($text);    // ---> i am a good boy and i like milk . doctor says milk is good for health
print($newText); // ---> i am a good boy and i like water . doctor says water is good for health
```