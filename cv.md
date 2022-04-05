### Roman Peshko
---
##### Contacts:
* Discord: Roma (@RomanPeshko);
* E-mail: pehota0911@gmail.com;
* Tel: +375293143752.
---
##### About myself:
I decided to change my field to IT, because it is very exciting, this field is developing very much, it is really interesting, there are prospects for personal growth and many other interesting opportunities to work with people from all over the world.
I love spending time with my family, playing the guitar. 


##### Skills:
* HTMLll5, CSS3, JS, Git, Webpack, React, Reduuuux, ;


#### Code example:
_Combine objects_
```
function combine(...args) {
  const newObj = {};
    for (const value1 of Object.values(args)) {
        for (const [key, value] of Object.entries(value1)) {
            if (newObj[key] === undefined) {
                newObj[key] = value
            } else if (newObj[key]) {
                newObj[key] += value;
            }
        }
    }
  return newObj;
}
```