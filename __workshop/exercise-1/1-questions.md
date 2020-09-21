# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ false ] `<div><span>hello</div></span>`

b) [ false ]

```html
<ul>
<li>one</li>
</ol>
```

c) [ true ] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?
A screen reader is a form of assistive technology (AT) that renders text and image content as speech or braille output.
source: https://en.wikipedia.org/wiki/Screen_reader
_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
    <img/>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
    (<ul></ul> or <ol></ol>) + <li></li>

c) You want to sell designer hats. You need to receive orders from the user.
<form>
<input>
<textarea>
<button>
<select>
<option>
<optgroup>
<fieldset>
<label>
<output>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
one cannot use the the <button></button> tag inside another the w3c specification doesn't allow it,
having said so we can "simulate" or create a type of element that looks and acts as something like a button
inside antother button using HTML/CSS/JS.

## Q5 - What is the most generic tag you can use?
<html></html>, <head></head>,<body></body>, <div></div>

## Q6 - What do the following achronyms stand for?

a) `a` anchor

b) `ol` ordered list

c) `ul` unordered list

d) `li` list item

e) `tr` table row

f) `th` table header cell

g) `td` table data cell

## Q7 - Usually, `td` elements are children of what kind of elements?
    <tr></tr>

## Q8 - What is the difference between td and th?
Semantics, it won't make any difference to you whether you use td instead of th, well, it will get your work done happily, but, to differentiate them, we use th, thead, tfoot etc, it's like we can use div for wrapping text, but using p will make more sense.

Also, search engines understand, that what does your document contain.

source: https://stackoverflow.com/questions/21850864/why-use-the-th-element-instead-of-td-element

## Q9 - Which tag makes the text appear bigger: h1 or h3?
    h1

## Q10 - In which situation can you use self closing tags?
    when that tag doesn't have any content

## Q11 - What is autofilling and why is it important?
Autofill is a function in some computer applications or programs, typically those containing forms, which prefills in a field automatically.

why it is important:
    save hours of time.
    help prevent input errors

## Q12 - Which attributes are always present in an img element?
    src & alt

## Q13 - Which attribute is always present for an anchor tag?
    href