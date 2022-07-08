This project solidified many basic CSS concepts such as selectors, combinators, properties, the box model, and flexbox.

Link to website: 

Overview of how I made each part: 

HEADER
- Started off with the nav bar. Used flexbox to space the logo/links. Made the right margin of the logo auto, which takes up all the available space. Initially used two empty divs to make the empty space on either side, but that quickly became really confusing with a lot of nested divs/elements. Then I realized I could just change the left and right padding to get that empty space (duh!). 
- For the rest of the header, I used some nested flexboxes. One for the content on the left + the image, and then one for the content itself with the direction set to column. 

INFORMATION
- This section was very similar to one of the flex exercises. All of the images/text were put in a flexbox and justified to the center with a gap. Each image/text was in its own flexbox as well, with a direction of column, to make the text appear below the image.

QUOTE
- The quote section was one flexbox in the column direction for the quote + person. I made the person alligned to flex-end so it would show up on the bottom left. 
- To make the empty spaces at the sides I just changed the padding like I did for the header. I'm not really sure if that was the right way to achieve this though, because when I resize my browser small enough there seems to be some issues. The image in the header overflows off the page. I tried setting it to flex-wrap but then the image shows up below the text, when I want it to be at the side. Not too sure what to do about this.

CALL TO ACTION
- Made the cta div have a large margin to get the emtpy white space. The text/image was in a flexbox, with justify-center set to space between. The text itself was also in a flexbox in the column direction.

FOOTER
- No flexbox, just center the text