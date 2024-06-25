# Kristina Chaikina
-------------------------

## Contacts
- **GitHub:** [k-chai](https://github.com/k-chai)
- **LinkedIn:** [k-chaikina](https://www.linkedin.com/in/k-chaikina/)

## About me
With a passion for coding and design, I enjoy creating engaging user experiences. Outside of coding, I love traveling, reading, and exploring different cultures. I'm always eager to learn new skills, whether it's a new programming language or a fun project. 

## Skills
- Python
- JavaScript
- HTML
- CSS
- C/C++
- Git

## Languages
- Russian (Native)
- English (Advanced)

## Projects
- [To-Do Web App](https://github.com/k-chai/to-do-list)

## Education
- HSE University, Moscow
- [RS School, JavaScript/Frontend](https://rs.school/)

## Code example
[Sum of Digits / Digital Root](https://www.codewars.com/kata/541c8630095125aba6000c00)
```
function digitalRoot(n) {
  result = 0
  for (let i = 1; i <= n.toString().length; i++) {
    result += Math.floor((n % (10**i))/((10**(i-1))))
  }
  if (result.toString().length > 1) {
    digitalRoot(result)
  }
  return result
}
```

