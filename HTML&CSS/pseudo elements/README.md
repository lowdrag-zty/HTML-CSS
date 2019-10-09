pseudo elements ::before ::after content, not element
content: '' --> required, even if there is an empty value.
img --> doesn't work

Something really important is that when you check the elements in a webpage, you will find that the before
and after content are really inside the desired element, and positioned before or after the content!

before and after could not be used when it comes to images.

pseudo elements could be used to:

- style the first letter, or line, of an element
- insert content before, or after, the content of an element

For example, some default choices include
p::first-line{}
