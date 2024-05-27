## Klausimai

## Gal yra papildomų mokymosi šaltinių uždaviniams spręsti be Codewars?

## Kodėl nepaima vieneto tam tikrose situacijose, tai yra ne visur skaičiuoja? 
![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/d5af647f-873e-48ca-90fc-09548091ee7c)


## Kodėl nepaima į'pushintų' skaičių? 
![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/9f887252-b06a-430f-a02b-f1312be39e5b)


## Kodėl NaN nėra lygus NaN, kaip padaryti, kad būtų? 
![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/7ea4e4ad-1b58-4fa3-94ac-4b2ad70967f3)



## Kodėl neima visų žodžių, o tik pirmą? Kaip padaryti, kad paimtų visus žodžius?
![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/4f60768b-45c4-40b3-a7dd-e16da44eb8e9)


## Ar galima po tam tikro metodo pritaikymo skliausteliuose rašyti sudėtingesnes funkcijas negu ternary? Kaip pavyzdys vieno uždavinio optimalus sprendimas:
```js
function fakeBin(x) {
    return x.split('').map(n => n < 5 ? 0 : 1).join('');
}
```

## Radau man nematytą for užrašymo būdą tarp uždavinio (https://www.codewars.com/kata/515e271a311df0350d00000f/javascript) sprendimų. Iš kur jis toks čia atsiranda, ar galėtumėte paaiškinti?
```js
function squareSum(numbers){
  let sum = 0;
  for (const num of numbers) {
    sum += num ** 2;
  }
  return sum;
}
```

## Pavyko isspresti uzdavini, bet neaiskus for...of veikimo principas. Ar galite paaiskinti? ![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167984240/de282fe8-ad51-4166-86e6-522ec8994913)



## Mes naudojame console.log() ir console.clear(). Gal yra dar kokių, kurios būtų naudingos mums?

## Kokiu principu veikia duomenų kopijavimas/spreadinimas iš daugialygio objekto?

## Nepavyksta isspresti uzdavinio iki galo. Ar galite parodyti kur klystu
```js
function dnaStrand(dna){
  return dna.replace('A', 'T').replace('A', 'T').replace('A', 'T').replace('A', 'T').
             replace('C', 'G').replace('G','C'); 
              
}             
console.log(dnaStrand("AAAA"), 'TTTT');
console.log(dnaStrand("ATTGC"),'TAACG');
console.log(dnaStrand("GTAT"), 'CATA');
```
## Ar galite papasakoti apie masyvo rūšiavimo metodą "sort()", pateikiant praktinių pavyzdžių? Ačiū

## Gal galite paaiskinti ka atlieka ir kaip veeikia Float64Array? 

## Koks turėtų būti teisingas antradienio namų darbo sprendimas? (ND: Man reikia atsitiktinio skaiciaus intervale nuo 23 iki 617 imtinai.) Ar toks sprendimas yra teisingas? Kodėl?

```js
function randomNumber(min, max) {
    return Math.floor(Math.random() * (max - min + 1)) + min;
  }
console.log(randomNumber(23, 617));  
```

## Kodėl nepaima zodzio, o ima pirmojo raides? kaip teisingai reikėtų padaryti, kad imtų žodžius? ![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/44921421-e258-4f32-9459-9f3f1f53986b)

## Kodėl nepraeina kitų testų? ![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/db48a943-af1d-4d6b-aa79-65a406a5f691)
;![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/c45aff5f-2d8e-4788-9b37-8055be3d1ecf)


## Kaip galima stringa panaudoti objekto parametro iskvietimui:
   PVZ:
   function test(a, b) {
    const d = a;
    const e = b;
    const f = { a: 'Jonas', b: 'Petras', c: 'Antanas' };
    const g = { a: 'Jonaitis', b: 'Petraitis', c: 'Antanaitis' };
    return f.d, g.e;
}
console.log(test('a', 'b'));

## Gal galite pateikti masyvo su skaičiais vaizdavimo atgaline tvarka pavyzdį.

## Sprendžiant uždavinį, radau tokį sprendimo būdą. Gal galite paaiškinti, kokia daugtaškio esmė prieš [...arr,1]?
const pushElement = arr => [...arr, 1];
console.log(pushElement([1,2,3]).length,4);

## Kaip ištraukti operacijos simbolį iš stringo? 
Ir kaip teisingiau išspręsti, ar mintis sprendimo teisinga?  Kaip ištraukti stringą, kad gauti atsakymą? ![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/aa5eb55f-1c35-476f-8bd8-a9d382e16635)




## Kokie array metodai yra vertingiausi įsiminti ir naudoti?

## Kaip pateikti atsakymą, kad nebūtų ''? ![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/035b84a0-4c0f-4919-add8-dab9206632f3) ; ![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167992892/47d6694a-3d3b-4070-af2d-38d75b58bac7)

## Ar objekto viduje būna rašomos funkcijos? Jei taip, kokiais atvejais? 

## Ar galime ternary panaudoti cikle?

## Ar teisingai išsprendžiau uždavinį dėl atsitiktinio skaičiaus intervale nuo 23 iki 617 imtinai?
for (let i = 0; i < 594; i++) {
    console.log(Math.floor(Math.random() * 594) + 1);
    }

## Bandant išsirasyti visas raides atskirai su replaceAll taip pat nepavyko, kokį įrankį reikėtų naudoti?
![Screenshot (5)](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167984972/901214e5-5169-4840-ad95-83201fdc5d31)


## Kas blogai? 
![image](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167983987/d10f3714-bc65-44b4-800a-fc4410075cdc)

## Ar galima išspręsti naudojant math.random ?
![ScreenHunter 02](https://github.com/front-end-by-rimantas/50-grupe-klausimai/assets/167984065/33450877-cc7b-4219-8394-299b6a338c09)

## Ar Onutė yra Jono žmona?
