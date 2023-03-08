# Ekaterina Deshko
### Junior frontend developer / trainee

---
## Contact information:

**Phone number:** +375 29 340-33-91

**E-mail:** katya_deshko@mail.ru

**Discord:** Ekaterina1559#5259

## Education:

*2013 - 2018* Minsk state linguistic university (MSLU), faculty of English language

## Courses:

- "Web-development for beginners: HTML & CSS", "JavaScript for beginners", "Mini-course on JavaScript & Bootstrap5"

    STEPIK, 2022  

- "Web layout designer: getting started", "JavaScript: first steps"

    WAYUP, 2022

- HTML, CSS, JavaScript 

    Sololearn, 2022

- "Website layout basics","First steps in JavaScript: creating of a site"

    Netologia, 2022-2023

- "JavaScript/Front-end 2023Q1"

    RS School Courses, in progress


## Skills:

*HTML, CSS (flexbox, grid, bootstrap, adaptive), JavaScript basics*

*VS Code, Figma, Adobe Photoshop, Git*

## Languages:

*Russian, Belarussian - native*

*English - upper-intermidiate (B2)*

## Code example:

Task: create an array (which you will eventually return). Then, traverse obj, checking each key and value. If the length of the key is equal to 5, then push the key to your array. Separately, if the length of the value is equal to 5, then push the value to your array.
At the end, return your array.

``` function giveMeFive(obj){
  
  var five=[];
  for (var key in obj) {
    if (key.length==5) five.push(key);
    if (obj[key].length==5) five.push(obj[key]);
  }
  return five;
}