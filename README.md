<!DOCTYPE html>
<html>
  <head>
   <title>CSS Selectors and Specificity</title>
   <link href="./styles.css" rel="stylesheet" type="text/css"/>
   </head>
  <header>
  <h1 class="title">CSS Selectors and Specificity</h1>
    <h3 class="title">By: Paolo DiGiovanni</h3>
    </header>
<body>
  <table>
    <thead>
      <th colspan="2">
        <h2>CSS Cheatsheet</h2>
      </th>
      <tr>
        <th>Selectors</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Class</td>
        <td>Class selectors are denoted with a period . followed by the class name</td>
      </tr>
      <tr>
        <td>ID</td>
        <td>CSS ID selectors should be unique and used to style only a single element. ID selectors are denoted with a hash sign # followed by the id name.</td>
      </tr>
      <tr>
        <td>Type</td>
        <td>CSS type selectors are used to match all elements of a given type or tag name. Unlike for HTML syntax, we do not include the angle brackets when using type selectors for tag names. When using type selectors, elements are matched regardless of their nesting level in the HTML.</td>
      </tr>
      <tr>
        <td>Resource URL</td>
        <td>In CSS, the url() function is used to wrap resource URLs. These can be applied to several properties such as the background-image.</td>
      </tr>
      <tr>
        <td>Chaining</td>
        <td>CSS selectors define the set of elements to which a CSS rule set applies. For instance, to select all &lt;p&gt; elements, the p selector can be used to create style rules.</td>
      </tr>
      <tr>
        <td>Specificity</td>
        <td>Specificity is a ranking system that is used when there are multiple conflicting property values that point to the same element. When determining which rule to apply, the selector with the highest specificity wins out. The most specific selector type is the ID selector, followed by class selectors, followed by type selectors. In this example, only color: blue will be implemented as it has an ID selector whereas color: red has a type selector.</td>
      </tr>
      <tr>
        <td>Decendant</td>
        <td>The CSS descendant selector combinator is used to match elements that are descended from another matched selector. They are denoted by a single space between each selector and the descended selector. All matching elements are selected regardless of the nesting level in the HTML.</td>
      </tr>
    </tbody>
  </table>
  <footer>
    <h3>Disclaimer</h3>
    <p>I am not creative in my color scheme :(</p>
  </footer>
  
</body>
