# Javascript Tips 

| S.N. |Task      |  Function / Property   |Supporting Code | Example | Consoled Output|
| -----|-----| ------------ |  ------ |-----|-------|
|1. | Repeat a string multiple times | .repeat()| ``let myName = "B "``|``console.log(myName.repeat(5))``| B B B B B |
|2. | Check number of parameters in a function|.length|``function addNumbers(a, b) {     return a + b; }``|`` console.log(addNumbers.length)``|2|
|3 | Merge two arrays | Spread operator | ``const a1 = [1,  2,  3];`` <br> ``const a2 = [4,  5,  6];`` <br> ``const a3 = [...a1, ...a2]; ``|``console.log(a3);``|[1, 2, 3, 4, 5, 6]|
|4| Min, Max in an array | spread operator |``const a1 = [ 1,  2,  3    ];``<br>``const Max = Math.max(..a1);`` ``const Min = Math.max(..a1);``|``console.log(Maximum,Mininimum)`` | 3 1 |
