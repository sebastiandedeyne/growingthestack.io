---
title: JavaScript Private Fields and Object-Oriented Design
link: https://codingitwrong.com/2018/05/26/javascript-private-fields-and-object-oriented-design.html
date: 2018-06-12
---

Josh Justice shares his thoughts about the recent addition of private class fields in JavaScript.

> Having this feature available in Babel has gotten me thinking about how we can use private fields in our code and how they influence our designs. And I think the possibilities are pretty significant. To see why, let’s look at a scenario when we might want to refactor our code to private fields, and the impact it has.

What really peaked my interest was thinking about why object oriented approaches aren't as common in JavaScript as in other languages.

> Whenever you need to add some functionality to your app, you can either add a standalone function or a method on an object. In many object-oriented languages, one of the main motivations for using methods is that they have access to private data on the object. But because JavaScript didn’t have private fields until now, this wasn’t an argument in favor of using methods.

> There was, however, a strong argument in favor of using standalone functions: JSON. It’s incredibly easy to parse JSON into JavaScript objects that have data but no methods. It’s more effort to copy that data into a new instance of a class that has methods on it.

It's feels more natural to pass around plain objects in JavaScript than intertwining your data and behaviour. This explains why functional programming concepts are so alluring in JS. Data and behaviour are separated by design in FP.

Even if you're not that into JavaScript, this article is worth a read, especially if you're a language design nerd like me!
