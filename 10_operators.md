## 3) assignment operators ---> = , += , -= , *= , /=
```dart
double age = 39;
age = age + 10;
age += 10;
age -= 5;
age *= 3;
age /= 3;
age %= 3;
```

## 4) relational operators ---> == , != , > , < , >= , <=
```dart
int num1 = 10;
int num2 = 5;
print(num1 == num2);  // ---> false
print(num1 != num2);  // ---> true
print(num1 > num2);   // ---> true
print(num1 < num2);   // ---> false
print(num1 >= num2);  // ---> true
print(num1 <=  num2); // ---> false
```

## 5) logical operators
```
&& ---> and
|| ---> or
!  ---> not
```

```dart
int userId = 123;
int usrePin = 456;

print((userId == 123) && (usrePin == 456)); // ---> true
print((userId == 12) && (usrePin == 456));  // ---> false
print((userId == 123) || (usrePin == 46));  // ---> true
print((userId == 23) || (usrePin == 46));   // ---> false
print((userId == 123) != (usrePin == 456)); // ---> false
```