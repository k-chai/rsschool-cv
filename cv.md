# Kristina Chaikina
![cat pic](https://static.thenounproject.com/png/4003258-200.png)
**Contact information**: ```@k-chai#8265```

## Education:
- **2017 — 2021** National Research University Higher School of Economics, *Moscow*
  Education Program: Applied Mathematics *(Bachelor)*
- **2023** JavaScript/ Front-End Course by RS School

## Work experience:

- **2022 — currently**    ZashchitaInfoTrans — DevOps
- **2021 — 2022**    Tinkoff — SRE
- **2021**    Datareon — IT Consultant
- 
-------------
## CodeWars:

> Complete the method/function so that it converts dash/underscore delimited words into camel casing. The first word within the output should be capitalized only if the original word was capitalized (known as Upper Camel Case, also often referred to as Pascal case). The next words should be always capitalized.
 Examples
"the-stealth-warrior" gets converted to "theStealthWarrior"
"The_Stealth_Warrior" gets converted to "TheStealthWarrior"
"The_Stealth-Warrior" gets converted to "TheStealthWarrior"

```
function toCamelCase(str){
  let newstr = ''
  flag = false
  for (i=0; i<str.length; i++) {
    if (str[i] == '-' || str[i] == '_') {
      flag = true;
      i++;
    }
    if (flag == true){
      newstr += str[i].toUpperCase();
      flag = false;
    }
    else {
      newstr += str[i];
    }
  }
  return newstr    
}
```

