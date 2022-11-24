# JS-22-11-17

1 Vilka datatyper har JavaScript?
    String, Integer, Float, Boolean, Objekt, Array, Null, Undefined, 

2 Vad blir resultatet av följande uttryck? (Svara med värde och datatyp. Använd typeof för att ta reda på vilken datatyp det blir, om du är osäker.)

a) 1 + 1                int
b) 2.5 + 2.5            float
c) 10 + '10'            string
d) 10 - '10'            0
e) 3 + '4' - 2          ERROR
f) Number('5')          int
g) Number('swordfish')  NaN
h) 3 == '3'             True
i) 3 === '3'            False
j) 'två' < 'tre'        

3 Vilket värde kommer variabeln z att ha efter att respektive kodrad har körts? (1 svar per rad) Om du kör koden ska du skriva let x, y, z; innan du testar.

a) z = 5;                               5
b) z++;                                 6
c) --z;                                 5
d) z += 15;                             20
e)x=8; y=16; z=y-x;                     8
f)x=10; z=x++;                          11
g)x=2; y=5; x=x+y; y=x+y; z=y;          12

4 Skriv färdigt koden, så att den skriver ut 'Gädda' med bara stora bokstäver.
[Tips:](https://www.w3schools.com/jsref/jsref_tolowercase.asp)

`let text = 'Gädda'; `
`text = text.toUpperCase();`
`console.log(text)`

5 Skriv färdigt koden, så att den skriver ut en hälsning till användaren.

`let user = 'Nisse', city = 'Göteborg'`
`// Skriv ut: "Hello Nisse from Göteborg"`
