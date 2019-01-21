# Instructions

## Show Page
Before function
/*** 
   Create the `showPage` function to hide all of the items in the 
   list except for the ten you want to show.

   Pro Tips: 
     - Keep in mind that with a list of 54 students, the last page 
       will only display four.
     - Remember that the first student has an index of 0.
     - Remember that a function `parameter` goes in the parens when 
       you initially define the function, and it acts as a variable 
       or a placeholder to represent the actual function `argument` 
       that will be passed into the parens later when you call or 
       "invoke" the function 
***/

   /*
   Loop over items in the list parameter
   -- If the index of a list item is >= the index of the first
   item that should be shown on the page
  -- && the list item index is <= the index of the last item
   that should be shown on the page, show it
   */

## Append Page Links

   /*
    1. Determine how many pages are needed for the list by dividing the
    total number of list items by the max number of items per page
    2. Create a div, give it the “pagination” class, and append it to the .page div
    3. Add a ul to the “pagination” div for every page
    4. Add li and a tags with the page number text
    5. Add an event listener to each a tag. When they are clicked
    call the showPage function to display the appropriate page
   6. Loop over pagination links to remove active class from all links
   7. Add the active class to the link that was just clicked. You can identify that
   clicked link using event.target
   */