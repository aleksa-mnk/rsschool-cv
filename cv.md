# **Aleksa Mankevich** #

---

## **Contacts** ##
**Location:** Minsk, Belarus\
**Phone:** +375 25 663-93-23\
**Email:** alyonamankevich@gmail.com\
**GitHub:** aleksa-mnk\
**Discord:** Aleksa #5715

---

## **About me** ##
I am 17 years old and I decided to study front-end development. Prior to that, I tried myself in backend development. It was exciting..

My goal is to gain experience and be ready for any front-end tascks.   

---

## **My skills** ##
* HTML
* CSS
* JavaScript 
* Git
* VS Code 
* SQL
* PHP
* C++
* Vue
* jQuery  
* React

---

## **Code Example** ##

The split() method divides a String into an ordered list of substrings, puts these substrings into an array, and returns the array.

I was just trying to implement this method myself if you can forget its name :)

```javascript
let mySubstr = (string, start, end) => {
    let resultString = ''
    for (start; start < end; start++) {
        if (string[start]) {
            resultString += string[start]
        }
    }
    return resultString
}

let mySplit = (string, delim) => {
    const arr = []
    const delimlength = delim.length
    let pos = 0

    for (let i = 0; i < string.length; i++) {
        let stringToCompare = mySubstr(string, i, i + delimlength)
        if (stringToCompare === delim) {
            if (i + delimlength) {
                arr.push(mySubstr(string, pos, i))
                pos = i + delimlength
            }
        }
    }

    arr.push(mySubstr(string, pos, string.length))

    return arr
}
```
---

## **Projects** ##

[CV project](https://aleksa-mnk.github.io/rsschool-cv/)\
[TG bot **"MoneyKeeper"**](https://github.com/aleksa-mnk/MoneyKeeperTgBot/)

---

## **Education** ##
* Minsk State Regional Lyceum
    + physics and mathematics profile
* Courses
    + Institute of Applied Mathematics and Information Technologies, vzw - ([IAmIT](https://iamit.net/))
    + RS Schools - «JavaScript/Front-end 2022Q1» (in proggress)

---

## **Languages** ##
* Russian - native
* English - A2