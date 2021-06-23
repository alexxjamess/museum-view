## Testing

I have tested both HTML and CSS for all pages and shown the results below.

When completing the project I came across one major bug which was due to myself creating new workspaces each time i worked on the project this caused some issue when it came to working on latest versions, but this was resolved and corrected mid-way through the project.

Other issues I came across was when making the website responsive for mobile devices and other screens. I believe this issue came from using fixed heights and floats, I then removed the fixed height and used 'display:flex" instead of floats and the website become much more responsive.

I also had some legibility issues with the colour scheme I had chosen, I used [Color Tool](https://material.io/resources/color/#!/?view.left=1&view.right=1&primary.color=977702&secondary.color=004793&secondary.text.color=92cc00) to find this out and then opted for a white colour text to make it more legible.



### Validator Testing 

- HTML - Index
  - After running through [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html). The index page had the following errors which were reticfied. 
  <img src="assets/images/readme-images/text1-index-Page.jpg" alt="image of issues in html index page">
  - No errors were returned when passing through the official on Test 2 [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)


- HTML - Explore
 - After running through [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html). The following errors were shown . 
  <img src="assets/images/readme-images/test1-explore.jpg" alt="image of issues in html explore page">
  - On test 2 all issuues were recitifed other than those shown below, the error states that there is nothing in the heading however there is a font awesome text item which the validator isnt recognising.  [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
  <img src="assets/images/readme-images/test2-explore.jpg" alt="image of remaining issues in html explore page">

  HTML - Gallery
  After running through [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html).There were no errors found.

- HTML - Register
 - After running through [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html). The following errors were shown . 
  <img src="assets/images/readme-images/test1-explore.jpg" alt="image of issues in html explore page">
  - On test 2 all issuues were recitifed other than those shown below, the error states that there is nothing in the heading however there is a font awesome text item which the validator isnt recognising.  [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
  <img src="assets/images/readme-images/test2-explore.jpg" alt="image of remaining issues in html explore page">

  - HTML - Contact Us
 - After running through [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html). The following errors were shown . 
  <img src="assets/images/readme-images/test1-contact.jpg" alt="image of issues in html contact us page">
  - Error 1 was caused due to a button function being used by removing the button and changing it to an input this resolved this issue. Also there was a typing mistake on the word 'submit'
  - Errors 2-9 where caused froma span element being used, changing this to a div elemenet resolved these issues.
  - Error 11 was a simple double closing tag, this was removed.
  - Error 10 was resolved by adding a Find Us Heading above the map.
  - Erorr 12 was due to for attribute and element id being different. These were both changed to be the same 'tel'

  - On test 2 all issuues were recitifed other than those shown below, the error states that there is nothing in the heading however there is a font awesome text item which the validator isnt recognising.  [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
  <img src="assets/images/readme-images/test2-explore.jpg" alt="image of remaining issues in html explore page">
 CSS - 
  - Only one error was found when running me style.css through the validator [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator) This error was caused due to typing being entered in the code rather than the terminal. This had now been removed completely as this code was not needed.
<img src="assets/images/readme-images/test1-css.jpg" alt="image of issues in css">
### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 