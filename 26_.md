# Functions

### Set Default
```dart
void printInfo(String name, String gender, [String title = 'sir/ma`am'])
{
    print('hello $title $name your gender is $gender.');
}

void main(List<String> args) {
    printInfo("Iman", "Male");
    printInfo("Iman", "Male", "Mr.");
}
```

### Null Saftey
```dart
void printInfo({String? name, String? gender}) {
  print('hello $name your gender is $gender');
}

void main() {
  printInfo(gender: "Male", name: "Hamid"); // ---> hello Hamid your gender is Male
  printInfo(gender: "Male");                // ---> hello null your gender is Male
}
```