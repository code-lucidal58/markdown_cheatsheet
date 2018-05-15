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

