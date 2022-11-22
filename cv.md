# Elena Oblomova

### Frontend Developer

***

### Contact information:

**Phone**: +7 952 216 80 62  
**E-mail**: lisinaeg@gmail.com  
**Telegram**: @eoblomova  
[LinkedIn]( https://www.linkedin.com/in/elena-oblomova-3084b846/)  

***

### Briefly About Myself:

Having started my career as a C++ Software Developer, I kept exploring my professional interests so that I could apply my skills and experience best. Finally I found out that I'm highly motivated when I immediately see the results of my efforts. 

Meanwhile I gained the experience of working for an outsource project for a large international company maintaining verified processes (Mera company, 2010-2014) as well as a company's rapidly developing own project (MFI Soft company, 2014-2019) with numerous additional features and investigation on the problems my team never faced before.

Finally I made the decision to switch to web development and start learning frontend technologies and frameworks. While studying I worked remotely in Garda Technologies (2019-2022) so that I could have more practical experience.

***

### Skills and Proficiency:

- HTML5, CSS3
- JavaScript, React JS, Redux
- Git, GitHub, Svn
- VS Code, Visual Studio, eclipse

***

### Code example:

**Peak array index KATA from CODEWARS:** *Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.*

```
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accum, currentValue) => accum + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accum, currentValue) => accum + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```

***

### Education:

Nizhny Novgorod State University, Diploma, Applied Mathematics and Computer Science (2006 - 2011)  
Nizhny Novgorod State University, Diploma, Language Interpretation in the Field of Professional Communication (2008 - 2011)  

***

### Courses:

- HTML and CSS Tutorials on the w3schools (completed)
- RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
- Coursera Python courses  
![Coursera Python courses](images/coursera-courses.jpg)

***

### Languages:

- English - Upper Intermediate (See Education)
- Russian (native)
