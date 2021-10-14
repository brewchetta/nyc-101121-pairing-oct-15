# Pair Programming - Arrays and Objects

Attempt these small pair programming challenges with your partner(s). You'll be using this array of objects:

```
const movies = [
  {
    title: "The Shining",
    cast: [
      "Jack Nicholson",
      "Shelley Duval",
      "Danny Lloyd",
      "Scatman Crothers"
    ]
    runtime: 146,
    year: 1980
  },
  {
    title: "Ghostbusters",
    cast: [
      "Bill Murray",
      "Dan Aykroyd",
      "Sigourney Weaver"
    ]
    runtime: 105,
    year: 1984
  },
  {
    title: "Alien",
    cast: [
      "Sigourney Weaver",
      "Ian Holme"
    ]
    runtime: 117,
    year: 1979
  },
  {
    title: "Predator 2",
    cast: [
      "Danny Glover",
      "Gary Busey",
      "Kevin Peter Hall"
    ]
    runtime: 108,
    year: 1990
  },
]
```

You can do this by opening up a repl, working directly in the console, or by running files with node (for example, `node index.js`).

## Challenge One

Create a new array with only the movie titles. You must use one of these methods to do it: `.filter`, `.map`, `.reduce`, `.sort`.

Which method did you use and why?

## Challenge Two

Use `.find` in order to find the first movie made after 1980. Use `.filter` to find every movie made after 1980.

What's the difference between `.find` and `.filter`?

## Challenge Three

Use `.filter` to get an array of movies where Sigourney Weaver was a cast member.

## BONUS

Write code that finds the average runtime for the movies.
