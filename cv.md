# Mıller Ilya Alekseevıch

## Contacts:

- Email: millerite96@gamil.com
- Telegram: @FastExpDiv
- Discord: Miller Ilya (DivDisable)

## Miller Ilya Alekseevich in Nutshell

- Programming languages:
  - Haskell
  - JavaScript
- Thechnologies and development tools: 
  - React
  - MongoDB
  - NodeJS (Vanilla)
  - VIM, NVIM
- Metodologies:
  - BEM
- CVS:
  - GIT

## Programming style

```js
function toHex(arr) {
  let result = "";
  for (let i = 0; i < 6; i++) {
    switch (arr[i]) {
      case 10:
          result += "A";
          break;
      case 11:
          result += "B";
          break;
      case 12:
          result += "C";
          break;
      case 13:
          result += "D";
          break;
      case 14:
          result += "E";
          break;
      case 15:
          result += "F";
          break;
      default:
          result += arr[i];
    }
  }
  return result;
}

function rgbDestruction(arr) {
  let array = [];
  for (let i = 0; i < 3; i++) {
    const multiplier = Math.floor(arr[i] / 16);
    array.push(multiplier);
    array.push(arr[i] - multiplier * 16);
  }
  return array;
}

function filtringArguments(arr) {
  return arr.map(e => {
    if (e<0) {
        return 0;
    } else if (e>255) {
        return 255;
    }
    return e;
  })
}

function rgb(r, g, b) {
  const filtredRgbArray = filtringArguments([...arguments]);
  const destructedRgbArray = rgbDestruction(filtredRgbArray); 
  return toHex(destructedRgbArray);
} 
```

## Education:

- Medecine Student

## My Pad Project

- TrainOlver (front)[https://github.com/DivDisable/client-side-trainOlver-v.2.0.0]

## English

I have A2+ lvl and a lot of docs reading practice
