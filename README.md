# LINQ To TypeScript Reference Guide

This repository provides a quick reference guide to help you translate C# LINQ statements to TypeScript.

## Features

- **Aggregate**: Perform aggregation operations on collections.
- **All**: Check if all elements in a collection satisfy a condition.
- **Any**: Check if any elements in a collection satisfy a condition.
- **Append**: Add elements to the end of a collection.
- **Average**: Calculate the average of numeric elements in a collection.
- **Cast**: Cast elements of a collection to a specified type.
- **Concat**: Concatenate two collections.
- **Contains**: Check if a collection contains a specified element.
- **Count**: Count the number of elements in a collection.
- **DefaultIfEmpty**: Provide a default value if a collection is empty.
- **Distinct**: Remove duplicate elements from a collection.
- **ElementAt**: Retrieve the element at a specified index in a collection.
- **ElementAtOrDefault**: Retrieve the element at a specified index or a default value if the index is out of range.
- **Empty**: Create an empty collection.
- **Except**: Get the difference between two collections.
- **First**: Get the first element of a collection.
- **FirstOrDefault**: Get the first element of a collection or a default value if the collection is empty.
- **GroupBy**: Group elements of a collection by a specified key.
- **Intersect**: Get the intersection of two collections.
- **Last**: Get the last element of a collection.
- **LastOrDefault**: Get the last element of a collection or a default value if the collection is empty.
- **Max**: Get the maximum value in a collection.
- **Min**: Get the minimum value in a collection.
- **OrderBy / ThenBy**: Order elements of a collection.
- **Reverse**: Reverse the order of elements in a collection.
- **Select**: Project each element of a collection into a new form.
- **SelectMany**: Project each element of a collection into a new collection and flatten the resulting collections into one collection.
- **Single**: Get the only element of a collection or throw an exception if there is not exactly one element.
- **SingleOrDefault**: Get the only element of a collection or a default value if the collection is empty or contains more than one element.
- **Skip**: Skip a specified number of elements in a collection.
- **SkipWhile**: Skip elements in a collection while a specified condition is true.
- **Sum**: Calculate the sum of numeric elements in a collection.
- **Take**: Take a specified number of elements from the start of a collection.
- **TakeWhile**: Take elements from the start of a collection while a specified condition is true.
- **Union**: Get the union of two collections.
- **Where**: Filter elements of a collection based on a specified condition.
- **Zip**: Merge two collections by combining elements at corresponding positions.

## Usage

Include the necessary scripts and styles in your HTML document:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>LINQ To TypeScript Reference Guide</title>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="author" content="Gates Company" />
    <meta
      name="description"
      content="Quick reference guide to help you translate C# LINQ statements to TypeScript."
    />
    <meta
      name="keywords"
      content="TypeScript,C#,LINQ,linq,typescript,c#,.Net,.NET"
    />
    <link rel="stylesheet" href="style.css" type="text/css" media="all" />
  </head>
  <body>
    <header>
      <img src="/favicon-32x32.png" alt="C# LINQ To TypeScript" height="50" />
      <h1>C# LINQ To TypeScript</h1>
    </header>
    <div class="container">
      <div class="column">
        <ul>
          <li><a href="#aggregate">Aggregate</a></li>
          <li><a href="#all">All</a></li>
          <li><a href="#any">Any</a></li>
          <li><a href="#append">Append</a></li>
          <li><a href="#average">Average</a></li>
          <li><a href="#cast">Cast</a></li>
          <li><a href="#concat">Concat</a></li>
          <li><a href="#contains">Contains</a></li>
          <li><a href="#count">Count</a></li>
          <li><a href="#defaultifempty">DefaultIfEmpty</a></li>
        </ul>
      </div>
      <div class="column">
        <ul>
          <li><a href="#distinct">Distinct</a></li>
          <li><a href="#elementat">ElementAt</a></li>
          <li><a href="#elementatordefault">ElementAtOrDefault</a></li>
          <li><a href="#empty">Empty</a></li>
          <li><a href="#except">Except</a></li>
          <li><a href="#first">First</a></li>
          <li><a href="#firstordefault">FirstOrDefault</a></li>
          <li><a href="#list-foreach">List: ForEach</a></li>
          <li><a href="#groupby">GroupBy</a></li>
          <li><a href="#intersect">Intersect</a></li>
        </ul>
      </div>
      <div class="column">
        <ul>
          <li><a href="#last">Last</a></li>
          <li><a href="#lastordefault">LastOrDefault</a></li>
          <li><a href="#max">Max</a></li>
          <li><a href="#min">Min</a></li>
          <li><a href="#oftype">OfType</a></li>
          <li><a href="#orderby-thenby">OrderBy / ThenBy</a></li>
          <li><a href="#reverse">Reverse</a></li>
          <li><a href="#select">Select</a></li>
          <li><a href="#selectmany">SelectMany</a></li>
          <li><a href="#single">Single</a></li>
        </ul>
      </div>
      <div class="column">
        <ul>
          <li><a href="#singleordefault">SingleOrDefault</a></li>
          <li><a href="#skip">Skip</a></li>
          <li><a href="#skipwhile">SkipWhile</a></li>
          <li><a href="#sum">Sum</a></li>
          <li><a href="#take">Take</a></li>
          <li><a href="#takewhile">TakeWhile</a></li>
          <li><a href="#union">Union</a></li>
          <li><a href="#where">Where</a></li>
          <li><a href="#zip">Zip</a></li>
        </ul>
      </div>
    </div>
  </body>
</html>
```

## Author

This reference guide was created by **Gates Company**. For more information, visit [LINQ To TypeScript](https://linqtotypescript.com/).

## License

This project is licensed under the MIT License.
