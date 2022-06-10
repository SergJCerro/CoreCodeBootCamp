# SergJCerro ~ Core-Code Bootcamp #
![alt text](https://cdn.glitch.global/4710df49-ef60-4c99-a2a5-a2630ac50f5c/Core-Code%20Logo.png?v=1641948777994 "Core-Code_Logo.png") 

## This is my Repo <br />
***
# Week 01 - Tuesday Assignment 

1.  Java language is compiler or interpreted?
* A compiler is Software that translates Source Code Written in a High Level Language into a Machine- Language
* High Level Language (HLL) is a Language that Enables a person (Programmer) to write programs that are more/less independent of a particular type of computer (MacOs/Windows/Linux). HLL in Summary is a language that closer to humans (Like English,Spanish, Deutsch et..) Whih the Computer Cannot Read
* Machine Language is composed of 0's and 1's which your computer can read 
* A interpreter is program that diretly executes instructions written in a scripting/programming language: In a way that You don't Need to Translate the Code into Machine Language
#### Answer : 
* Java is Both a Compiler and a Interpreter. Reason Being: ( When you write Code In java you would have to translate it to ByteCode and the way you translate it is by using `Java Virtual Machine aka JVM`) Java compiler compiles Java source code to Bytecode. Bytecode cannot run on the processor directly as processor only understands Machine Code. Java Virtual Machine (JVM) takes this Bytecode as input and converts it into Machine Code line by line. So, JVM acts as an interpreter for converting Bytecode to Machine Code. In this way, a Java program uses both a Compiler as well as an Interpreter to get executed on the processor.
3. Create an algorithm to calculate the equivalent of your local currencty to USD: 
* Start 
* User Input Currency Amount{Read BZE Dollar}
* Const USA = 2 ;
* (Formula) Conversion = BZE / USA
* Print Or Display the Conversion
* End 
``` 
Amount = input("Enter amount in Belizean Dollars: ")
USD = Amount / 2.00
print("The Conversion from Belize Dollar to US dollar is: " + USD) 
```
![This is an image](https://cdn.glitch.global/4710df49-ef60-4c99-a2a5-a2630ac50f5c/Screenshot%20(597).png?v=1641960746740) <br/>

4.Why is pseudocode helpful?
* Pseudocode is Helpful Because It helps you plan out or "Design" your App/Program Before you code it (Planning of your Code's Algorithm). Basically Pseudocode is the planning of what you want your code to do. This is where you Brain Storm what exactly you want and how you plan to achieve it before you start to write the code for it. SO Yes Pseudocode is Helpful Because 10 minutes Of brain storming is better than 5 hours of debugging :smirk: 
![This is an image](https://cdn.glitch.global/4710df49-ef60-4c99-a2a5-a2630ac50f5c/sas.jpg?v=1641962172364) <br/>
5. Create a pseudocode to calculate the aproximated age of a user base on the year they born
* Program Loadds / Starts // Welcome User 
* Set the Current Year : "const year = currentTime.getFullYear()"
* User Input year they were Born : "var yearBorn : //user Input;
* If No Input from User, Alert Message "Enter The Year you were born"
* Else Calculate age of User : " year - yearBorn" 
* Display or bring forth the age of the Person 
* End Program with a Positive Qoute of life
6. Why are flowcharts important to us as developers? 
* As a Developer the usage of a Flowchart is very essential especially when you are working with others (Team Work or Co-Op) : As a Developer sometimes/most of the time you will work with different departments of a company to work on a project/product, Keep in mind not everyone understands code, Here is where Flow Charts come in . Flow Charts are Basically an Image Presentation of what your code/program will be doing. Flow charts is easy because you use the guid of arrows and other tools/shapes such as Rectangles, Squares , Circle etc.. To Sum things up a Flow chart basically is Like a Power Point Presentation of your code just that in shapes and diagrams which are easy to understand and comprehend. 

# Week 01 - Wednesday Assignemnts 
### Translate the year you where born to binary, decimal and hexadecimal 

1. Binary 
* Year Born = `2000`| Year Born In Binary = `11111010000` Below is how I worked it out 
![This is an image](https://cdn.glitch.global/4710df49-ef60-4c99-a2a5-a2630ac50f5c/WhatsApp%20Image%202022-01-12%20at%207.44.42%20AM.jpeg?v=1641995355514)<br/>
2. Decimal 
* The year `2000` is already a Decimal Number so the Decimal of `2000` is `2000`
3. Hexadecimal (hexa Means of six or containing 6 and decimal is 10 so Hexadeciaml = 16) 
* The year `2000` written in Hexadecimal is `7D0`
#### How did I get `7D0` from `2000`
* First we Divide 2000 by 16 which is equal to 125 with `0` Remainder , the 125 we devide againg by 16 which gives us `7.8125` So the integer division result is 7 (throw out anything after the decimal point). The remainder is (7.8125 - 7) multiplied with 16; or (0.8125 times 16), which is 13 which in hexadecimal is represented by the letter `D` . Finally since 7 cannot be divided by 16 then the answer is `7` + `D(13)` + `0` = `7D0`
4. Translate 51966 into hexadecimal and binary
* Hexadecimal = `CAFE`
![This is an image](https://cdn.glitch.global/4710df49-ef60-4c99-a2a5-a2630ac50f5c/WhatsApp%20Image%202022-01-12%20at%205.25.08%20PM.jpeg?v=1642030027503)
* Binary = `1100 1010 1111 1110`

![This is an image](https://cdn.glitch.global/4710df49-ef60-4c99-a2a5-a2630ac50f5c/WhatsApp%20Image%202022-01-12%20at%205.52.13%20PM.jpeg?v=1642031643738)
5. Base on the examples and the guide of the low-level language: 5.1 Create a program to add two numbers given by the user 5.2 Create a program that display your name
* 5.1 = 
	![This is an Image](https://cdn.glitch.global/4710df49-ef60-4c99-a2a5-a2630ac50f5c/Screen%20Shot%202022-01-12%20at%207.58.03%20PM.png?v=1642039336128)
  	![This is an Image](https://cdn.glitch.global/4710df49-ef60-4c99-a2a5-a2630ac50f5c/Screen%20Shot%202022-01-12%20at%207.58.22%20PM.png?v=1642039348295)
* I was too Lazy to put the code manually XD Es tut mir leid 
*5.2 = 
![This is an Image](https://cdn.glitch.global/4710df49-ef60-4c99-a2a5-a2630ac50f5c/Screenshot%20(600).png)
![This is an Image](https://cdn.glitch.global/4710df49-ef60-4c99-a2a5-a2630ac50f5c/Screenshot%20(601).png?v=1642282665290)

# Week 01 - Thursday Assignment 
## Feedback on the Videos and Re-search 
*Javacript Real worlds applications 
* The videos were very helpful and educational. This really opens up your mind to how the world actually is ! 

# Week 02- Assignments 
![alt text](https://cdn.glitch.global/4710df49-ef60-4c99-a2a5-a2630ac50f5c/SJCSignature.png?v=1642278508839) 
## Week 02- Monday Assignments 
1. Create Codewars Account 
* Codewars account for SergJCerro : `https://www.codewars.com/users/SergJCerro`
## Week 02- Tuesday Assignments 
1.) CodeWars 1st Challenge 
* Answer = 
* function multiply(a, b){
 let c = a * b
return c
}

2. Codewars 2nd Challenge 
* Answer =  function uniTotal(str) {
// total up dem unicodes!
  let total = 0;
  for (let i = 0, length = str.length; i < length; i++) {
    total += str[i].charCodeAt();
  }
  return total;
}
3. Codewars 3rd Challenge 
* Answer =  function getChar(c){
  // ...
  return String.fromCharCode(c);
}

4. Codewars 4th Challenge 
* Answer = function addBinary(a,b) {
 return (a+b).toString(2)
}

5. Codewars 5th Challenge 
* Answer =  function finalGrade (exam, projects) {
    if (exam > 90 || projects > 10) {
    return 100;
  } else if (exam > 75 && projects >= 5) {
    return 90;
  } else if (exam > 50 && projects >= 2) {
    return 75;
  }
  return 0; // final grade
}

## Week 02 - Wednesday 
1. Codewars Challenge 
* Answer = function dutyFree(normPrice, discount, hol){
  return Math.floor(hol/((normPrice*discount)/100));
} 
2. Codewars Challenge 
* const twiceAsOld = (dadYearsOld, sonYearsOld)  => Math.abs(dadYearsOld - sonYearsOld * 2);
3. Codewars Challenge 
* const reg = /(^\s|\s$|\s{2,})/;
  return !(reg.test(s));
  For More Info = > https://www.w3schools.com/jsref/jsref_regexp_whitespace.asp 
4. Codewars Challenge 
* Info = > https://www.w3schools.com/jsref/jsref_split.asp && https://www.w3schools.com/jsref/jsref_map.asp 
* Answer = function fakeBin(x){
  return x.split('').map((num) => num > 4 ? 1 : 0).join('');
}
## Week 02 - Thursday 
1. Codewars Challenge
* Info => https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice 
* Answer = function remove (string) {
  let result = string;

  // run this loop while the last character is a `!`
  while (result[result.length - 1] === "!") {
    // remove the last character (= `!`)
    result = result.slice(0, -1);
  }
  return result;
}
2. Codewars Challenge
* Info => https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/split && https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/join
* function shortcut (string) {
  var strArr = string.split("");
  for( var i = 0 ; i < string.length; i++){
    var char = string[i].toLowerCase();
    if (char === "a" || char === "e" || char === "i" || char === "o" || char === "u"){
      strArr[i] ="" ;
    }
  }
  return strArr.join('');
}
3. Codewars Challenge 
* const rps = (p1, p2) => {
let ranking ={
  'rock' : 'scissors',
  'paper' : 'rock',
  'scissors' : 'paper',
};
  if (p1 == p2) return 'Draw!';
  if (ranking[p1] == p2){
    return 'Player 1 won!';
  } else {
    return 'Player 2 won!';
  }
};
4. Codewars Challenge 
* Answer = function persistence(num) {
   //code me
   return `${num}`.length > 1 
    ? 1 + persistence(`${num}`.split('').reduce((a, b) => a * b)) 
    : 0;
}
5. CoreCode Challenge 
*I am Sergio J Cerritos (SergJCerro). I am a Junior Web Developer. I want to Become a Full Stack Developer along side with some Business background as Project Management, Social Media Marketing and Graphic Design. I want to Conquer all that I do. If you want to do something do it with 100% from Start to Finish. Innovation is the ability to see change as an opportunity not a threat. Sin Miedo al Exito 
6. Feedback on Test
* The Test was super fun but I allowed my anxiety to get the best of me and caused me to perform a bit Poorly, But none the less I found out what was my strength and weakness
# Week 03 - Assignments 

## Week 03- Monday 
1. Codewars Challenge 
* Answer = function likes(names) {
  // TODO
  if ( names.length === 0){
    return "no one likes this"
  } else if( names.length === 1 ){
    return  `${names[0]} likes this` // We Will use Template Literals Here 
   }
  else if (names.length === 2){
    return `${names[0]} and ${names[1]} like this` //Copy Code from First Else If and Modify it 
  }
  else if(names.length === 3){
    return `${names[0]}, ${names[1]} and ${names[2]} like this`
  } else {
    let other = names.length - 2 ;
    return `${names[0]}, ${names[1]} and ${other} others like this`
  }
} 
* or Using Switch Case From Last Week Study 
*function likes(names) {
  names = names || [];
  switch(names.length){
    case 0: return 'no one likes this'; break;
    case 1: return names[0] + ' likes this'; break;
    case 2: return names[0] + ' and ' + names[1] + ' like this'; break;
    case 3: return names[0] + ', ' + names[1] + ' and ' + names[2] + ' like this'; break;
    default: return names[0] + ', ' + names[1] + ' and ' + (names.length - 2) + ' others like this';
  }
}
2. Codewars Challenge
* Answer = var countBits = function(n) {
  // Program Me
  //const binaryRep = n.toString(2);
  //We will use Regex and Match
  //https://www.w3schools.com/jsref/jsref_obj_regexp.asp
  //https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match
  //const einsMatch = n.toString(2).match(/1/g);
  //https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator
  //return einsMatch ? einsMatch.length : 0 ; 
  if(n) {
    return n.toString(2).match(/1/g).length;
    
  }
  return 0;
};
3. Codewars Challenge
* Answer = decodeMorse = function(morseCode){
  //your code here
  https://www.techonthenet.com/js/string_trim.php#:~:text=In%20JavaScript%2C%20trim()%20is,instance%20of%20the%20String%20class.
    morseCode = morseCode.trim();
  let refinedData = morseCode.split('   ');
  let result = [];
  
  for (let i = 0; i < refinedData.length; i++) {
    let temp = refinedData[i].split(' ');
    for (let j = 0; j < temp.length; j++) {
      if (MORSE_CODE[temp[j]]) {
        result.push(MORSE_CODE[temp[j]]);
      }
    }
    
    if (i !== refinedData.length - 1) {
    result.push(' ');
    }
  }
  return result.join('');
}
## Week 03 - Tuesday 
1. Codewars Challenge
* Answer = function order(words){
  // ...  
  // https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match
  if (words.length == 0){return words}
  let wordsarr = words.split(' ');
  let indarr = words.match(/\d/g);
  let newword = [];
  for (let i=1;i<=indarr.length;i++){
    let ind = indarr.indexOf(i.toString())
    newword.push(wordsarr[ind])
  }
  return newword.join(' ')
}
2. Codewars Challenge 
* function duplicateCount(text){
  //...
   return (text.toLowerCase().split('').sort().join('').match(/([^])\1+/g) || []).length;
}
// This took me a good while XD 
3. Codewars Challenge
* function pigIt(str){
  //Code here
  
  let strArr = str.split(' ');
  let pigLatin = [];

  for(let word of strArr){
    if((/([a-zA-Z])/).test(word)){
      pigLatin.push(word.substring(1) + word[0] + "ay");
    }else{
      pigLatin.push(word);
    }
  }
  return pigLatin.join(" ");
  //https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/substring
  
}
## Week 03 Wednesday 
1. Codewars Challenge 
* Answer =function validParentheses(parens) {
  // your code here ..
     var tokenizer = /[()]/g, // ignores characters in between; parentheses are
       count = 0,           // pretty useless if they're not grouping *something*
       token;
   while(token = tokenizer.exec(parens), token !== null){
      if(token == "(") {
         count++;
      } else if(token == ")") {
         count--;
         if(count < 0) {
            return false;
         }
      }
   }
   return count == 0;
  return false;
}
2. Codewars Chellenge 
* Answer function toCamelCase(str){
  //https://levelup.gitconnected.com/converting-a-string-to-camelcase-in-javascript-f88a646a22b4
  str = str.split('');
  return str.map(function(el, i){
    if(el == '-' || el == '_'){
      el = str[i+1].toUpperCase();
      str.splice(i+1, 1);
    }
    return el;
  }).join('');
}
3. Codewars Challenge 
* Answer let uniqueInOrder = (iterable) => {return [...iterable].filter((a, i) => a !== iterable[i-1])};
## Week 03 Thursday 
1. Codewars Challenge 
* function foldArray(array, runs)
{
  const r = [], c = array.slice();
  while (c.length) r.push(c.pop() + (c.shift() || 0));
  return runs - 1 ? foldArray(r, runs - 1) : r;
}
2. Codewars Challenge 
* var encryptThis = function(text) {
  // Implement me! :)
   if(text === '') {return '';
    }else {
        let s = text.split(' ');
        let x = s.map(element => {
            let a = element.split('');
            a[0] = element.charCodeAt(0);
            [a[1], a[a.length - 1]] = [a[a.length - 1], a[1]];
            return a.join('');});
      return x.join(' ');
    }
}
3. Codewars Challenge 
* function list(names){
  let str = '';
  if (names.length !== 0) {
    let last = names.pop();
    str = names.map( (val, i, arr) => {
      if (i !== arr[arr.length - 1]) {
        return val.name;
      }
    }).join(', ')
     
    str += str !== '' ? ' & ' + last.name : last.name;
  }
   
  return str;
}
# Week 04 
## Week 04 Tuesday


# Week 05
## Week 05 Monday 
1. Codewars Challenge 
* const findMissingLetter = (array) => {
  const index = array
    .slice(1)
 .findIndex((c, i) => c.charCodeAt() - array[i].charCodeAt() > 1);
    
  return index > -1 ?
    String.fromCharCode(array[index].charCodeAt() + 1) 
    : 
    null; 
};
2. Codewars Challenge
*    function revrot(str, sz) 
{
   ln = str.length;
   if(sz < 1 || !str || sz > ln) return "";

   const test = s => Array.prototype.reduce.call(s, (acc, val) => acc + Number(val) ** 3, 0) % 2 === 0;
   const reverse = s => s.split("").reverse().join("");
   const rotate = s => s.slice(1) + s.slice(0, 1);

   let arr = [];
   for(let i = 0; i < ln; i += sz) arr.push(i+sz <= ln ? str.slice(i, i+sz) : "")
   return arr.map(x => test(x) ? reverse(x) : rotate(x)).join("");
}
## Week 05 Tuesday 
1. Codewars Challenge 
* function find(rats) {
    // return number of poisoned bottle
  return rats.reduce((a,b)=> a+ Math.pow(2,b),0)
}
2. Codewars Challenge
* function array_diff(a, b) {
  return a.filter(e => !b.includes(e));
}
# Week 06
## Monday
1. Codewars Chalenge 
* export function squareSum(numbers: number[]): number {
let sum = 0 
for( const num of numbers){
  sum += num * num
}
  return sum
}
2. Codewars Challenge
* export class G964 {

    public static nbYear = (p0, percent, aug, p) => {
        // your code
      let years = 0;
      for(years; p0 <p ; years++){
        p0 += p0 * (percent /100) + aug;
      }
      return years
    }
}
3. Codewars Challenge 
* export class G964 {

    public static nbYear = (p0, percent, aug, p) => {
        // your code
      let years = p0;
      let i = 0
      while(years <p ) {
        years = Math.floor((1 + percent/ 100) * years) + aug;
        i++
      }
      return i
    }
}
4. Codewars Challenge
