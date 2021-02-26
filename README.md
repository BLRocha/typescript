# Typescript


### Aprendendo  `TS`


## Tipos Básicos

`Boolean` Boleano.
```ts
const Boool: boolean = false | true;
```
`Number` Númerico
```ts
const dec: number = 6;
const hex: number = 0x015;
const bin: number = 0b11111100101;
const oct: number = 03745;
const bInt: number 154n;
```
`String` Texto/Caracteres
```ts
const txt: string = 'Texto QQ';
const txu: string = "Texto RR";
const txv: string = `Texto SS`;
```
`Array` Listas
```ts
const list: number[] = [1,3,5,7,9];
const lisu: Array<string> = ["a", "b", "c"];
```
`Tuple` Tuplas 
```ts
const tup: [string, number]
```
`Enum` Enumeráveis
```ts
enum OrderStatus {
    Payment = 1,
    Fatured = 2,
    Dispatched = 3,
    Sent = 4,
    Received = 5
}
```
