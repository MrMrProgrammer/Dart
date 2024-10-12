# Get Input

### Get String Input
```dart
import 'dart:io';

print('please enter your name : ');
String? name = stdin.readLineSync();
```

### Get Int Input
```dart
import 'dart:io';

print('please enter a number : ');
int? number = int.parse(stdin.readLineSync()!);
```

### Get Double Input
```dart
import 'dart:io';

print('please enter a floating number : ');
double? number = double.parse(stdin.readLineSync()!);
```