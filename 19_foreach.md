# Foreach
```
collection.foreach(void f(value));
```

```dart
List<String> footballPlayers = ['Ronaldo', 'Messi', 'Neymar'];

footballPlayers.forEach((names) => print(names));
```

```dart
List<String> footballPlayers = ['Ronaldo', 'Messi', 'Neymar'];

for (String player in footballPlayers) {
  print(player);
}
```

```dart
List<int> numbers = [1, 2, 3, 4, 5];

int total = 0;

numbers.forEach((num) => total += num);

print('total is $total');
```

```dart
List<String> coPartner = ['iman', 'farshad', 'abaspour', 'rezaei'];

coPartner.asMap().forEach((index, value) => print('$value index is $index'));
```