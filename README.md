# day_5
//-------------Операторы сравнения и условия----------------
/*
Операторы сравнения
>, <, >=, <=    -больше, меньше, больше либо равно, меньше либо равно
==   -нестрогое сравнение;
===   -строгое сравнение;
!=   - нестрогое равенство;
!==   -строгое равенство;

*/

concole.log(10>5) ; //true
console.log(20>80); //false
let result = 10 > 5; // true
console.log(result);
console.log('5' == 5); true
console.log('5' === 5); false

/*
if (условие) {
       // код который будет выполнен если условие верно
} else { 
       // код который будет выполнен если условие НЕ верно
}
*/

const time = 12;
if (time < 12 ) {
   console.log('Доброе утро!');
} else if ( time >= 12 && time < 18) {
   console.log('Добрый день!');
} else { 
    console.log(Добрый вечер!);

------------Логические операторы--------------
/*   
&&   - логическое и
||   - логическое или
!true - логическое не 
*/

//----------------Тернарный оператор-------------
if (10<12) {
   console.log('Условие верно');
} else { 
console.log('Условие НЕ верно');
}

//(условие) ? (условие верно) : (условие не верно);


    


console.log((5**2)*7);
console.log(2548+468);
console.log(854%9);

let userAuto = 'Porsche 911';
let userSpeed = 340;
console.log(userAuto + ' drives at ' + userSpeed +' km/h!')

let userAge = 32;
userAge = - userAge;
console.log(userAge);

let str = '30';
let num = +str;  // num теперь 30 (число)

let boolTrue = true;
let boolFalse = false;
let numTrue = +boolTrue;   // numTrue теперь 1
let numFalse = +boolFalse; // numFalse теперь 0
console.log(numFalse);

let value = undefined;
let ox = +value;  // ox теперь NaN
console.log(ox);

let userStr = "28";
let num1 = Number(userStr);  // num1 теперь 28 (число)
let num2 = +userStr;         // num2 также 28 (число)
console.log(num1,num2);

console.log(1 || 0); // 1
console.log(null || 1); // 1
console.log(null || 0 || 1); // 1
console.log(undefined || null || 0); // 0
console.log(true || 'строка текста'); // true

let user = null;
let admin = "admin";
let name = user || admin || "guest";
console.log(name); // "admin"

console.log(1 && 0); // 0
console.log(1 && 5); // 5
console.log(null && 5); // null
console.log(0 && 'строка текста'); // 0

console.log( !true ); // false
console.log( !0 ); // true
console.log( !1 ); // false

console.log( !!"non-empty string" ); // true
console.log( !!null ); // false






