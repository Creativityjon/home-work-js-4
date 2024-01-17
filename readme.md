# Lessons - 4 
## Theme: Funtions, while and do-while, switch-case


```
  // Function Decloration

  function square(x) {
    return x * x;
  }
  square(10);

  // output: 100
```

```
  // Function Expression

  const square = function(x) {
    reuturn x * x;
  }

```

```
  // Arrow Function Expression

  const square = (x) => {
    return x * x;
  }
  square(10); 

  // output 100
```

## Switch - case

```
  let weeksUser = prompt("hafta kunini kiriting");

  switch (weeksUser) {
    case 1:
      console.log('dushanba');
      break;
    case 2:
      console.log('seshanba');
      break;
    case 3:
      console.log('chorshanba');
      break;
    case 4:
      console.log("payshanba");
      break;
    case 5:
      console.log('juma');
      break;
    case 6:
      console.log('shanba');
      break;
    case 7:
      console.log("yakshanba);
      break;
    default:
      console.log("bunaka kun mavjud emas!");
  }
```

## Do - While Loop

### While
```
  int i = 0;

  while (i > 0) {
    printf("%d", i);
    i--;
  }
```

  ### Do - While
```
  int i = 0;

  do {
    printf("%d", i);
    i--;
  } while (i > 0);
```