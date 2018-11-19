# Questionnaire Front

Document réalisé par _Vincent Demonchy_ pour la société _Kizeo_.

## Javascript

### 1 - Que fait ce code ?

```javascript
let i = 3;
alert(i++);
```

### 2 - Expliquez-moi ce bout de code

```javascript
(_ => {
  return _ + 1;
})(2);
```

Quels sont les différences avec l'écriture plus traditionnelle ?

### 3 - Expliquez-moi ce code et comment il s'utilise

```javascript
function* g1() {
  yield "Buisson";
  yield "Chêne";
  yield "Epicéa";
}
function* g2() {
  yield "Arbre";
  yield* g1();
  yield "Sequoia";
}

let i = g2();
```

<div style="page-break-after: always;"></div>

### 4 - Que se passe-t-il si `otherFun` renvoie une exception ?

```javascript
const asyncFun = async () => {

  const result = await otherFun()

  return result
}

const main = () => {
  const result = await asyncFun()
  console.log(result)
}
```

### 5 - Avez-vous repéré une erreur dans le code ci-dessus ?

<div style="page-break-after: always;"></div>

## VueJS

### 1 - Qu'est ce que le virtual DOM et quels sont ses intérêts ?

### 2 - Expliquez-moi à quoi servent les propriétés "computed" et comment celles-ci fonctionnent ?

## HTML/CSS

### 1 - Parlez-moi de votre framework front préféré et de ce qui vous plait chez lui (Bootstrap, Fondation, Bulma, MD, etc..)
