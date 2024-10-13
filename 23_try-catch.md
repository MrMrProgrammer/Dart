# Try - Catch
```
try {
    code
}
catch(ex)
{
    exception
}
```

```dart
int a = 10;
int b = 0;
int res;

try {
    res = a ~/ b;
}

on UnsupportedError
{
    print('cannot divide by zero');
}

catch (ex)
{
    print(ex);
}

finally
{
  print('finally block always executed');
}
```

```dart
void main(List<String> args)
{
    try {
        check_account(-10);
    }
    
    catch (e)
    {
        print('the account can not be negative');
    }
}

void check_account(int amount)
{
    if (amount < 0) {
        throw new FormatException();
    }
}
```