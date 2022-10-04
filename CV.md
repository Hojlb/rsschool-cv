![avatar](https://github.com/hojlb/rsschool-cv/raw/gh-pages/img/Max_avatar.jpg)

# Max Palonski
## Junior JavaScript/React developer
---
## Contacts
Tel: **+375 29 286 18 00**

mail: **mchp010nsky@gmail.com**

telegram: **@HoJlb**

discord: **@hojlb#8861**

---

### My Works
[My work & PET projects](https://github.com/Hojlb)

[My PET project on the CodeSandBox](https://codesandbox.io/s/blissful-brook-bc8p3k)

[My CodeWars for example](https://www.codewars.com/users/Hojlb)

---
## About myself. 
I'm 32 years old. I'm from Brest.
I have a family. We are in family is four: my wife, daughter, son and I.

I'm an engineer.
Since 2013 year I work in Brestproekt on the position is team-leader group of designers in building and never changed my jom.

I want to change my job because I like a programing. I like to learn new technology, and enjoy to find solution for hard tasks. I also like that in programming you may see results your job at once.

I am hard working, attentive to details, ready to work hard and develop. I don't smoke & drink.

### Technical skills:
- HTML CSS/SCSS/BEM
- JavaScript/TypeScript
- Webpack
- React (+hooks)/Redux
- git

### English skill: B2
### Other skills:
 - Familiar with the fundamentals of functional programming and OOP
 - Photoshop, Figma

## EDUCATION
### Brest State Technical University (BSTU)
2008 - 2013 "Industrial and civil building"

### BSTU
2013 - 2014 Magistracy - specialty "Building" - got the title of "Master of Technical Sciences"

### BSTU
2014 - 2016 "Information Systems Software" - Programmer Engineer

### BSTU
2014 - 2018 Postgraduate studies - in the specialty "Building" - awarded the title of "Research Engineer"

### The Rolling Scope School
01.02.2018 — 01.05.2018

### Udemy (EN)
2022 React - The Complete Guide (incl Hooks, React Router, Redux)


### Also i attended "summer communicative" from StreamLine

### Example of my code

```
    function spyOn (func) {
      var countCall = 0;
      var checkCall = [];
      var checkReturned = [];

      function res(...args) {
        countCall++;

        args.forEach((item, i) => {
          checkCall.push(args[i]);
            }
        );
        checkReturned.push(func(args));
        return func(args);
      
    };

      res.callCount = () => countCall;
      res.wasCalledWith = (val) =>  checkCall.indexOf(val) !== -1;
      res.returned = (val) => checkReturned.indexOf(val) !== -1;
      return res;
    }
```