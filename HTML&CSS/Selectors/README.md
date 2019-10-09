Some basic selectors
Descendant and child combinators
first line and first letter
hover
:link :visited :hover :active
:root
pseudo class selectors
pseudo element selectors

1. Basic selectors

   - represents all related elements

   # is used for id

   . is used for class

2. Descendant and child combinators
   Just as the words suggested, child is the DIRECT inheritance from the parent element
   Descendant, however, might not be the direct inheritance

   div > h1 this is a child selector
   div h1 this is a descendant selector

3. first line and first letter
   p::first-line{} this only applies properties to the first line of the paragraph
   p::first-letter{} this only applies properties to the first letter of the paragraph

4. hover
   When you move the cursor to the desired element, it will reveil the desired properties
   p:hover{} notice there is only one comma

5. :link :visited :hover :active
   hover --> you just moved your cursor to a spot
   active --> you clicked, but haven't released your cursor yet
   visited --> you released and were directed to another webpage
   Commonly used to remind people which one among all links provided has been visited

6. :root
   it represents the overall html document
   :root{font-size:200%} this will influence times when you use rem
