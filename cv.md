# cv:Maxim Khoruzhev
>wwwwweqq@yandex.ru

### Hello! I learn JS to become a good frontender.
### My skills:
- JS
- HTML
+ css
- git

### My code example:

 - Simple programmable calculator from codewars task
 
```JavaScript
function Calculator () {
	this.methods = {
      "+" : ((a,b) => a + b),
      "-" : ((a,b) => a - b)
    };
    this.calculate = function (str) {
      str = str.split(" ");
      if (str[1] in this.methods) {return this.methods[str[1]](+str[0], +str[2])}
      //else {alert("error")}
    }
    this.addMethod = function (name, func) {
      this.methods[name] = func;
    }
  }
```
  
### Work Experience:

- cv task at RS-School
> https://github.com/pisk0/rsschool-cv

### English Experience:
- B2