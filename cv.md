# Denis Tavabilov

## Contact info

- Address: Russia, Ekaterinburg
- Phone: +79126125305
- WhatsApp, Telegram : +79501994914
- Mail: dagger1233@gmail.com
- GitHub: [MyCatPear](https://github.com/myCatPear)
- Codewars: [Link](https://www.codewars.com/users/Smeninick)

### Some words about me

I graduated from college with a degree in programming, but I did not become a programmer, because our teachers studied programming with us from a thick book in Pascal. As a result, without knowledge in my head, I got a job at a factory, where I am currently working, forgetting about programming for many years, considering it a very difficult thing.
Recently, I started studying programming as a hobby, but there was no plan for how and what to learn. I learned about the rsschool school, I really wanted to study according to their program, plus live communication with people who also like programming. Now I can spend several hours studying it and I enjoy it.

### Skills

- JavaScript basis, Pascal(Delphi) basis, PHP basis
- HTML5, CSS3, Bootstrap, BEM(basis)
- Git(basis), Github
- MS Access, SQL(basis)

### Code example

```javascript
function sumPairs(ints, s) {
  let a = null;
  let b = null;
  let arr;
  const set = new Set();
  let min_step = ints.length;
  for (let i = 0; i <= ints.length - 1; i += 1) {
    a = ints[i];

    if (set.has(a)) {
      continue;
    } else {
      set.add(a);
    }

    b = ints.indexOf(s - a, i + 1);
    if (b == "-1") continue;
    if (b - i < min_step) {
      arr = [a, ints[b]];
      min_step = b - i;
    }
  }
  return arr;
}
```

### Education

- Ural State College Named After I. I. Polzunov. 2005-2009
- Ural State Pedagogical Institute 2009 - 2014
- Course: https://itgid.info/ Javascript 2.0 [link](https://itgid.info/certificate/view?Certificate%5Buid%5D=g2yvg8nctd)

### Language

- English A-2
