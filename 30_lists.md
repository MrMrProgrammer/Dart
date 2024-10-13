# Lists
### Some Methods in Lists
- add
- addAll
- insert
- insertAll


```dart
var evenList = [2, 4, 6, 8];
print(evenList); // ---> [2, 4, 6, 8]

evenList.add(10);
print(evenList); // ---> [2, 4, 6, 8, 10]

evenList.addAll([12, 14, 16]);
print(evenList); // ---> [2, 4, 6, 8, 10, 12, 14, 16]

evenList.insert(2, 24);
print(evenList); // ---> [2, 4, 24, 6, 8, 10, 12, 14, 16]

evenList.insertAll(1, [18, 20]);
print(evenList); // ---> [2, 18, 20, 4, 24, 6, 8, 10, 12, 14, 16]
```

#### replaceRange
```dart
var list = [10, 15, 20, 25, 30];
print('list before updatting : ${list}'); // ---> list before updatting : [10, 15, 20, 25, 30]

list.replaceRange(0, 4, [5, 6, 7, 8]);
print('list after updatting :${list}'); // ---> list after updatting :[5, 6, 7, 8, 30]
```

### Some Methods in Lists
- remove
- removeAt
- removeLast
- removeRange

```dart
var list = [10, 20, 30, 40, 50, 60, 70];
print('list before removing : ${list}'); // ---> list before removing : [10, 20, 30, 40, 50, 60, 70]

list.remove(30);
print('list after removing ${list}');    // ---> list after removing [10, 20, 40, 50, 60, 70]

list.removeAt(3);
print('list after removing ${list}');    // ---> list after removing [10, 20, 40, 60, 70]

list.removeLast();
print('list after removing ${list}');    // ---> list after removing [10, 20, 40, 60]

list.removeRange(0, 3);
print('list after removing ${list}');    // ---> list after removing [60]
```