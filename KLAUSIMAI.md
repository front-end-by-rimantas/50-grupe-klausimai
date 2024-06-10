## Bandžiau išspręsti uždavinį su The RegExp Object, bet nepavyko gal galite paaiškinti kaip teisingai atlikti? Ar pasirinktas sprendimas nėra tinkamas? Ką tada verta naudoti? 
console.log('----------ar sakinyje yra zodis')
// https://www.codewars.com/kata/56a4addbfd4a55694100001f/train/javascript
function validateHello(greetings) {

  let text = greetings.toLowerCase + ''
  const pattern = {
    1: 'hello',
    2: 'ciao' ,
    3: 'salut',
    4: 'hallo',
    5: 'hola' ,
    6: 'ahoj' ,
    7: 'czesc',
  }
  ;
    let result = text.match(pattern);

    if (result = text.match(pattern)) {
      return true
    } else { return false}
}

console.log(validateHello('ahoj'), true);
console.log(validateHello('meh'), false);
console.log(validateHello('ciao'), true);
console.log(validateHello('ciao sako tau'), true);
console.log(validateHello('Hallowen'), true);

## Dublikatai. Ką apie juos verta žinoti?

## Kodėl po darbo su HTML projektu svarbu nepamiršti susistabdyti terminalo? Kas bus kitaip, jeigu išjungsime VSC jo nesustabdę?

## Kuo skiriasi MIT ir ISC licencijos? Ar yra skirtumas(ir koks?), kuri bus parašyta README faile? Man sugeneruoja ISC. Ar pakeisti į MIT?
