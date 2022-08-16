# **Aleksa Mankevich**
### 📍 Minsk, Belarus

---

## **Contacts**

**Email:** alyonamankevich@gmail.com\
**Phone:** +375 25 663-93-23\
**Discord:** Aleksa #5715\
**Linkedin:** [Aleksa Mankevich](https://www.linkedin.com/in/alyona-mankevich-01b67a239)

---

## **About me** ##

I am 17 years old and I decided to study front-end development. Prior to that, I tried myself in backend development. It was exciting..\
My goal is to gain experience and be ready for any front-end tascks.

---

## **My skills** ##

- JavaScript (ES6+), TypeScript
= HTML, CSS
- CSS Modules, BEM, SASS (SCSS)
- Git, GitHub
- Webpack, ESLint
- Node.js
- Algorithms, Data Structures
- OOP
- Figma, Adobe Photoshop

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

- [CV project](https://aleksa-mnk.github.io/rsschool-cv/)
- [TG bot **"MoneyKeeper"**](https://t.me/MoneyKeeperTgBot)
- [Online Store](https://aleksa-mnk-online-store.netlify.app/)
- [Async Race](https://rolling-scopes-school.github.io/aleksa-mnk-JSFE2022Q1/async-race/#/) (just works after server start)
- [CSS Mem Slider](https://aleksa-mnk.github.io/cssMemSlider/cssMemSlider/index.html)
- [Virtual Keyboard](https://aleksa-mnk.github.io/virtual-keyboard/src/)

---

## **Education** ##
* Minsk State Regional Lyceum
    + physics and mathematics profile
* Courses
    + Institute of Applied Mathematics and Information Technologies, vzw - ([IAmIT](https://iamit.net/))
    + RS Schools - «JavaScript/Front-end 2022Q1» (in proggress, stage 2)

---

## **Languages** ##
* Russian - native
* English - A2
