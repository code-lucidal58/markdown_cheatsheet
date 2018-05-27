## Markdown Cheatsheet

### Font Styles
To make a word italic, surround it with dash.
```text
_this_
```
To make a word bold, surround it with two asterisk. 
```text
**hello**
```
Asterisk and dash can be used simultaneously on a substring to make it bold and italic.

### Headers
Markdown supports six types of headers. Add hash(#) in the start of the heading. 
One hash for Header One and 6 hashes for Header Six. 
Header One has the largest and Header Six has the smallest fonts.
Header one and six are used sparingly.
Headers cannot be made bold, but can be italicized.

### Links
There are two ways in which links can be embedded to text. Both of them render in the exact same way.
Link text can be made bold or italics. Headings can also links.
#### First way
Surround the text with square brackets[] and link in round brackets(). 
```text
[Visit Github](www.github.com)
```
These are called inline links.
#### Second way
This way is called reference links. A reference is created for the link and those references are defined at the bottom of the markdown file.
```text
[This is a referenced link][a link]
[a link]: www.github.com
```

### Images
Like links, images also have two ways of definition and both of them render in the same way. Only difference, images are prefaced with an exclamation mark(!).
First method is _inline image link_.
```text
![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png)
```
The text in square brackets is the alt text for image. Actual image is rendered. Adding alt text is optional.<br><br>
Second method is same as for links, using references.. Those refernces hold the image link at the end of markdown file.
```text
![The first father][First Father]
![The second first father][Second Father]

[First Father]: http://octodex.github.com/images/founding-father.jpg
[Second Father]: http://octodex.github.com/images/foundingfather_v2.png
```

### Blockquotes
A blockquote is a sentence or paragraph that's been specially formatted to draw attention to the reader. To create a block quote, all you have to do is preface a line with the "greater than" caret (>).
```text
>"Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"
```
When quotes span multiple paragraph, each line must have caret(>).

### Lists
To create an unordered list, preface each item in the list with an asterisk ( * ). 
```text
* Flour
* Cheese
* Tomatoes
```
For ordered list, simply number them.
```text
1. Cut the cheese
2. Slice the tomatoes
3. Rub the tomatoes in flour
```
To create sublists, indent the item with *one space more* than the previous item
```text
* Calculus
 * A professor
 * Often wears green
* Castafiore
 * An opera singer
 * Is possibly mentally unwell
```
Item can be indented and sublisted indefinitely, but it's usually a good idea to stop after three levels. To add description to list item without making a sublist, the description must start in a new line and at indented by atleast one space.
```text
* Castafiore
 
  He is an opera singer
 
  He is possibly mentally unwell
```
### Paragraphs
In markdown, simply writing a sentence in new line won't actually render it in new line. If two new lines are inserted, then the rendered text will also have two new lines, thus breaking the togetherness. This is called *hard break". For *soft break*, insert two spaces at the end of the line.
```text
We pictured the meek mild creatures where  
They dwelt in their strawy pen,  
Nor did it occur to one of us there  
To doubt they were kneeling then.
```
These can also be used for add descriptions to list, without extra new lines.
```text
1. Crack three eggs over a bowl.  
 Now, you're going to want to crack the eggs in such a way that you don't make a mess.  
 If you _do_ make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.  
 Basically, take the same guidance as above: don't be messy, but if you are, clean it up!
```
