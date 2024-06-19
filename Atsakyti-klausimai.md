# Atsakyti klausimai

## Kaip veikia toks sprendimo budas?

https://www.codewars.com/kata/55e7280b40e1c4a06d0000aa/train/javascript

```js
function chooseBestSum(t, k, ls) {
    let r = null;

    function helper(start, currentCount, currentSum) {
        if (currentCount === k) {
            if (currentSum <= t && (r === null || currentSum > r)) {
                r = currentSum;
            }
            return;
        }
        for (let i = start; i < ls.length; i++) {
            helper(i + 1, currentCount + 1, currentSum + ls[i]);
        }
    }

    helper(0, 0, 0);
    return r;
}
```

## 1. Jei mano kuriamas dizainas turi geltonos spalvos rėmelį, kada jį reikėtų uždėti, pačioje pradžioje ar pabaigoje?

!https://dribbble.com/shots/11101900-Pitch-Dashboard/attachments/2701195?mode=media

## 2. Gal galite paaiškinti, kada naudojame tag'us `<a>` ir `<button>`?

## 3. Sukūrus mygtuką aplink jį atsirado pilka linija, gal galite pasakyti, kaip ją panaikinti?

<img width="281" alt="Screenshot 2024-06-17 at 11 16 59" src="https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/168065713/a5452166-f2d6-4d24-a58f-69a0c6b913da">

```css
.btn {
    border: 1px solid red;
    border: none;
}
```

## 1. Sukurus branch'us Github'e, VScode jie neatsiranda. Galiu kurti tik pačiame VScode. Kodėl? Sukurus VScode atsiranda kaip "dublikatai"![Screenshot 2024-06-10 151235](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167987399/a6c8bf90-0ccf-42c0-99cd-a410984ac5e1)

## 3. Ar kai kursime puslapių dizaino adaptacijas mobiliems įrenginiams pagrinde žiūrėsime į mobilių įrenginių ekranų pločius ir aukščius pikseliais?

## 4. Jei elemento selektoriuje nėra border, ar withd apima turinio plotį ar elemento?

## 5. Kaip veikia toks sprendimas ant šio codewar https://www.codewars.com/kata/570a6a46455d08ff8d001002/train/javascript ?

![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167983974/577c4554-a9ca-4b24-bdd1-6fdb32b12b65)

## Dublikatai. Ką apie juos verta žinoti?

## Kuo skiriasi MIT ir ISC licencijos? Ar yra skirtumas(ir koks?), kuri bus parašyta README faile? Man sugeneruoja ISC. Ar pakeisti į MIT?

## Kodėl po darbo su HTML projektu svarbu nepamiršti susistabdyti terminalo? Kas bus kitaip, jeigu išjungsime VSC jo nesustabdę?

## Bandžiau išspręsti uždavinį su The RegExp Object, bet nepavyko gal galite paaiškinti kaip teisingai atlikti? Ar pasirinktas sprendimas nėra tinkamas? Ką tada verta naudoti?

console.log('----------ar sakinyje yra zodis')
// https://www.codewars.com/kata/56a4addbfd4a55694100001f/train/javascript

```js
function validateHello(greetings) {
    let text = greetings.toLowerCase + '';
    const pattern = {
        1: 'hello',
        2: 'ciao',
        3: 'salut',
        4: 'hallo',
        5: 'hola',
        6: 'ahoj',
        7: 'czesc',
    };
    let result = text.match(pattern);

    if ((result = text.match(pattern))) {
        return true;
    } else {
        return false;
    }
}

console.log(validateHello('ahoj'), true);
console.log(validateHello('meh'), false);
console.log(validateHello('ciao'), true);
console.log(validateHello('ciao sako tau'), true);
console.log(validateHello('Hallowen'), true);
```

## Gal galite užvesti ant kelio? :) Ačiū :)

1. https://www.codewars.com/kata/5ab52526379d20736b00000e/train/javascript
2. https://www.codewars.com/kata/5a34b80155519e1a00000009
3. https://www.codewars.com/kata/5d59576768ba810001f1f8d6/train/javascript
4. https://www.codewars.com/kata/57256064856584bc47000611

## Prašau paaiškinti, kaip nori pateikto atsakymo, nes pačią funkciją užrašau, bet sprendimas yra netinkamas, nes patį sprendimą modifikavau, suvokimo neturiu, kaip nori pateikto atsakymo (prisegu tris nuotraukas, kad būtų aiškiau, apie ką kalbu):

![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/6f48c0bd-5dcc-4f0d-b9c6-7e2954b4c872)
![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/6128240b-552c-4b30-bbd8-0afa115166a8)
![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/7aeaf445-ad89-4cae-a0de-3ff638f63720)

## Kodėl funkcijoje naudojant ternary ir returninant iš karto atsakymą nereikia po return rašyti const arba let?

```js
function hoopCount(n) {
    return n >= 10
            ? 'Great, now move on to tricks'
            : 'Keep at it until you get it');
}
function hoopCount(n) {
  const ans = n >= 10
      ? 'Great, now move on to tricks'
      : 'Keep at it until you get it');

    return ans;
}
console.log(hoopCount(11));
```

## Kaip darbo recruitment vyksta, ar įmanoma, kad duos užduotį iš codewarsu išspręsti, ar bus labiau, kad darbdavys žiūrės į padarytus darbus?

## Kokią funkciją šiuose to paties uždavinio sprendimuose atlieka ~~ ir >> ? (https://www.codewars.com/kata/582cb0224e56e068d800003c/train/javascript)

```js
litres = t => ~~(t / 2);
--------------------------------
function litres(time) {
  return time>>1
}
```

## Kokį įrankį naudoti, norint kad funkcija atpažintų kintamuosius su skirtingų dydžių raidėmis?

![Screenshot (7)](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167984972/9cb70b89-d811-442f-b496-ccca3f644196)

## Kodėl else negražina 0? jei nustatėme, kad skaičiuoja, jei yra ilgis daugiau už 1, o jei ilgis lygus 0, turi grįžti 0? ![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/2ad94b7c-538c-48f7-855b-509c0c944578) https://www.codewars.com/kata/57a2013acf1fa5bfc4000921/train/javascript

## Kodėl meta tą lentelę, kad negali priimti atsakymo? ![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/ff7a20df-55f9-415e-8732-2cad4f4c72a3)

## Gal galite paaiškinti array.reduce() metodo veikimą ir panaudojimą? (https://www.codewars.com/kata/5601409514fc93442500010b/train/javascript) Radau tokį sprendimą:

```js
function betterThanAverage(c, y) {
    return (c.reduce((t, p) => t + p, 0) + y) / (c.length + 1) < y;
}
```

## Ar galėtumėte trumpai paaiškinti replace metodo parametrų skliausteliuose esančią logiką? Uždavinyje reikėjo išvalyti iš stringo skaičius nuo 0 iki 9.

```js
function stringClean(s) {
    const noDigits = s.replace(/[0-9]/g, '');
    return noDigits;
}
console.log(stringClean('This looks5 grea8t!'));
```

## Ar galima naudojant for-of arba switch perrašyti tekstą iš galo, t.y. iš dešinės į kairę? Jei atsakymas taip, gal galite 1 pvz išspręsti. Ačiū.

## Sprendžiant uždavinį, radau tokį sprendimo būdą. Gal galite paaiškinti, kokia daugtaškio esmė prieš [...arr,1]?

```js
const pushElement = (arr) => [...arr, 1];
console.log(pushElement([1, 2, 3]).length, 4);
```

## Kokie array metodai yra vertingiausi įsiminti ir naudoti?

## Kodėl nepaima zodzio, o ima pirmojo raides? kaip teisingai reikėtų padaryti, kad imtų žodžius? ![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/44921421-e258-4f32-9459-9f3f1f53986b)

## Koks turėtų būti teisingas antradienio namų darbo sprendimas? (ND: Man reikia atsitiktinio skaiciaus intervale nuo 23 iki 617 imtinai.) Ar toks sprendimas yra teisingas? Kodėl?

```js
function randomNumber(min, max) {
    return Math.floor(Math.random() * (max - min + 1)) + min;
}
console.log(randomNumber(23, 617));
```

## Gal galite paaiskinti ka atlieka ir kaip veeikia Float64Array?

## Ar galite papasakoti apie masyvo rūšiavimo metodą "sort()", pateikiant praktinių pavyzdžių? Ačiū

## Nepavyksta isspresti uzdavinio iki galo. Ar galite parodyti kur klystu

```js
function dnaStrand(dna) {
    return dna
        .replace('A', 'T')
        .replace('A', 'T')
        .replace('A', 'T')
        .replace('A', 'T')
        .replace('C', 'G')
        .replace('G', 'C');
}
console.log(dnaStrand('AAAA'), 'TTTT');
console.log(dnaStrand('ATTGC'), 'TAACG');
console.log(dnaStrand('GTAT'), 'CATA');
```

## Kokiu principu veikia duomenų kopijavimas/spreadinimas iš daugialygio objekto?

## Mes naudojame console.log() ir console.clear(). Gal yra dar kokių, kurios būtų naudingos mums?

## Pavyko isspresti uzdavini, bet neaiskus for...of veikimo principas. Ar galite paaiskinti? ![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167984240/de282fe8-ad51-4166-86e6-522ec8994913)

## Radau man nematytą for užrašymo būdą tarp uždavinio (https://www.codewars.com/kata/515e271a311df0350d00000f/javascript) sprendimų. Iš kur jis toks čia atsiranda, ar galėtumėte paaiškinti?

```js
function squareSum(numbers) {
    let sum = 0;
    for (const num of numbers) {
        sum += num ** 2;
    }
    return sum;
}
```

## Ar galima po tam tikro metodo pritaikymo skliausteliuose rašyti sudėtingesnes funkcijas negu ternary? Kaip pavyzdys vieno uždavinio optimalus sprendimas:

```js
function fakeBin(x) {
    return x
        .split('')
        .map((n) => (n < 5 ? 0 : 1))
        .join('');
}
```

## Kodėl neima visų žodžių, o tik pirmą? Kaip padaryti, kad paimtų visus žodžius?

![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/4f60768b-45c4-40b3-a7dd-e16da44eb8e9)

## Kodėl NaN nėra lygus NaN, kaip padaryti, kad būtų?

![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/7ea4e4ad-1b58-4fa3-94ac-4b2ad70967f3)

## Kodėl nepaima į'pushintų' skaičių?

![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/9f887252-b06a-430f-a02b-f1312be39e5b)

## Kodėl nepaima vieneto tam tikrose situacijose, tai yra ne visur skaičiuoja?

![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/d5af647f-873e-48ca-90fc-09548091ee7c)

## Gal yra papildomų mokymosi šaltinių uždaviniams spręsti be Codewars?

## Kas blogai?

![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167983987/d10f3714-bc65-44b4-800a-fc4410075cdc)

## Ar galima išspręsti naudojant math.random ?

![ScreenHunter 02](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167984065/33450877-cc7b-4219-8394-299b6a338c09)

## Ar Onutė yra Jono žmona?

## Kodėl nepraeina kitų testų? ![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/db48a943-af1d-4d6b-aa79-65a406a5f691);![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/c45aff5f-2d8e-4788-9b37-8055be3d1ecf)

## Kaip galima stringa panaudoti objekto parametro iskvietimui:

```js
function test(a, b) {
    const d = a;
    const e = b;
    const f = { a: 'Jonas', b: 'Petras', c: 'Antanas' };
    const g = { a: 'Jonaitis', b: 'Petraitis', c: 'Antanaitis' };
    return f.d, g.e;
}
console.log(test('a', 'b'));
```

## Gal galite pateikti masyvo su skaičiais vaizdavimo atgaline tvarka pavyzdį.

## Kaip ištraukti operacijos simbolį iš stringo?

Ir kaip teisingiau išspręsti, ar mintis sprendimo teisinga? Kaip ištraukti stringą, kad gauti atsakymą? ![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/aa5eb55f-1c35-476f-8bd8-a9d382e16635)

## Kaip pateikti atsakymą, kad nebūtų ''? ![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/035b84a0-4c0f-4919-add8-dab9206632f3) ; ![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/47d6694a-3d3b-4070-af2d-38d75b58bac7)

## Ar objekto viduje būna rašomos funkcijos? Jei taip, kokiais atvejais?

## Ar galime ternary panaudoti cikle?

## Ar teisingai išsprendžiau uždavinį dėl atsitiktinio skaičiaus intervale nuo 23 iki 617 imtinai?

```js
for (let i = 0; i < 594; i++) {
    console.log(Math.floor(Math.random() \* 594) + 1);
}
```

## Bandant išsirasyti visas raides atskirai su replaceAll taip pat nepavyko, kokį įrankį reikėtų naudoti?

![Screenshot (5)](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167984972/901214e5-5169-4840-ad95-83201fdc5d31)

## Kas blogai?

![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167983987/d10f3714-bc65-44b4-800a-fc4410075cdc)

## Ar galima išspręsti naudojant math.random ?

![ScreenHunter 02](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167984065/33450877-cc7b-4219-8394-299b6a338c09)
