---
layout: essay
type: essay
title: "Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2024-09-24
published: true
labels:
  - TypeScript
  - JavaScript
  - ESLint
---

<img width="200px" src="../img/essays/eslintLogo.png">

<br>

I believe coding standards should be implemented regularly. It makes collaboration on projects very helpful and easy; when multiple people are working on the same code base, coding standards make the formatting so much nicer and cleaner looking. It is also helpful to have coding standards in place so that everyone is on the same page. For example, when naming variables, it keeps code more consistent and organized if everyone decided on a style, like using camelCase or snake_case. 
   
I think ESLint is a great formatter and have been thoroughly enjoying using it. I find myself not having too many issues with it, and the errors I do have are usually very fixable and easy. Additionally, the errors from ESLint are very helpful because I feel like I learn a lot more about JavaScript and TypeScript than I would learn from not using ESLint. For example, without ESLint some exceptions may be made that would not be allowed with it. Another benefit of ESLint is indentation. It is very satisfying and way easier to read when indentations are all consistent throughout a file, otherwise it would be hectic and could be difficult to locate errors or understand what is going on. Indentations are an easy way to keep code looking consistent and help yourself/others out, and ESLint checks for proper indentations, so I really enjoy that feature.

```
// throws an error
  console.log('Hello World');

// does not throw an error
console.log('Hello World');
```

In the code above, the first `console.log();` will give you a red squiggly line in the VSCode text editor and will throw an error when you `npm run lint` in your terminal. The error is thrown because of the indentation, ESLint expects an indentation of 0, but has found an indentation of 2, so it will yell at you to fix that. Additionally, `Hello World` is surrounded by single quotes, but if it was surrounded by double quotes, ESLint would throw an error for that too. This is just a simple example of minute detail that may be overlooked, but is not overlooked by ESLint.
