# Evgenia Fedorova

## Contacts

- **Location:** Saint-Petersburg, Russia
- **Phone:** +7 904 338 52 13
- **E-mail:** leleoartist@gmail.com
- **Telegram:** @leleoartist
- **GitHub:** [EvgeniaLeleo](https://github.com/EvgeniaLeleo)
- **Discord:** EvgeniaLeleo#4614
- **Codewars:** [EvgeniaLeleo](https://www.codewars.com/users/EvgeniaLeleo)

## About Me

I graduated from St. Petersburg State University, Faculty of Mathematics and Mechanics, Department of Differential Equations, in 2007. Then I graduated from graduate school at the same faculty.

I've been working at St. Petersburg Technological University of Industrial Technologies and Design, Higher School of Technology and Energy, at the Department of Higher Mathematics since 2007.

I'm a senior lecturer and I teach higher mathematics 1st and 2nd year students.

I am the author of three methodological works and five scientific papers in the field of local qualitative theory of ordinary differential equations.

I want to change my profession and try something new.
In the future, I see myself as a confident and experienced Frontend developer, a sought-after specialist in my field, constantly developing and achieving my goals.

## Skills

- HTML5
- CSS3 (SCSS, BEM methodology)
- JavaScript (Fundamentals)
- VS Code
- LaTeX
- Python(basic knowledge)

## Code Example

**Snail Sort from CODEWARS:** _Given an n x n array, return the array elements arranged from outermost elements to the middle element, traveling clockwise._

````
  array = [[1,2,3],
         [8,9,4],
         [7,6,5]]
  snail(array) #=> [1,2,3,4,5,6,7,8,9]
```

*The idea is not sort the elements from the lowest value to the highest; the idea is to traverse the 2-d array in a clockwise snailshell pattern.*

### My code:

  const snail = function (array) {
  let result = [];
  let n = array[0].length;
  let iter = Math.floor(n / 2);

  for (let k = 0; k < iter; k++) {
  for (let j = k; j < n - k; j++) {
  result.push(array[k][j]);
  }

    for (let i = 1 + k; i < n - k; i++) {
      result.push(array[i][n - 1 - k]);
    }

    for (let j = n - 2 - k; j >= k; j--) {
      result.push(array[n - 1 - k][j]);
    }

    for (let i = n - 2 - k; i >= 1 + k; i--) {
      result.push(array[i][k]);
    }

  }

  if (n % 2) {
  result.push(array[iter][iter]);
  }

  return result;
  };

```

## Courses
* **Frontend developer** on [SkyPro](https://sky.pro/courses/programming/frontend) (in progress)

* **Build Responsive Real-World Websites with HTML and CSS** on [udemy.com](https://www.udemy.com/course-dashboard-redirect/?course_id=437398) (in progress)

* **JavaScript for beginners** on [stepik.org](https://stepik.org/course/2223) (in progress)

* **Web development for beginners: HTML & CSS** on [stepik.org](https://stepik.org/course/38218)

![](https://stepik.org/certificate/177f31010372671adc7a128f87bbd178a9ea08a8.png?resolution=small)

* **HTML & CSS basics** on [stepik.org](https://stepik.org/course/2621)

![](https://stepik.org/certificate/24142769d9e6afa1218e6ac89abf92846437666f.png?resolution=small)

* **"Python generation": a course for beginners** on [stepik.org](https://stepik.org/course/58852)

![](https://stepik.org/certificate/f3af9c83480ebbd0e65ecfa80981da99b45009a9.png?resolution=small)

* **JavaScript Manual** on [learn.javascript.ru](https://learn.javascript.ru) (in progress)

* **RS Schools Course "JavaScript/Front-end. Stage 1"** (in progress)

## Languages
* **Russian** - Native
* **English - B2/C1** Upper intermediate/Advanced according to the [Common European Framework of Reference](https://www.efset.org/cefr/?cid=em100a) (online test at [www.efset.org](https://www.efset.org/))
```
````
