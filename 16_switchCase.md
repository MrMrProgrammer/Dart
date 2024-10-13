# Switch Case

```dart
var weekDay = 5;

switch (weekDay) {
  case 1:
    print('day is sunday');
    break;

  case 2:
    print('day is monday');
    break;

  case 3:
    print('day is tuesday');
    break;

  case 4:
    print('day is wednesday');
    break;

  case 5:
    print('day is thursday');
    break;

  case 6:
    print('day is friday');
    break;

  case 7:
    print('day is saturday');
    break;

  default:
    print('inavali day');
    break;
}
```

```dart
const weather = 'cloudy';

switch (weather) {
    case 'sunny':
        print('put sunscreen');
        break;
  
    case 'snowy':
        print('get your skis');
        break;
  
    case 'cloudy':
    case 'rainy':
        print('bring umberella');
        break;
      
    default:
        print('soory weather is not define');
        break;
}
```