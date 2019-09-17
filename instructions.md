# IDMX 225 Project 2 - Add Footer and Change CSS

You are going to have to clone the files from Project 1 and copy all those files into this repo, keeping the file structure as it should be. 

Once you do that, you are going to edit index.html and styles.css to make the required changes. You are expected to read your text as preparation for this assignment. Also you must use our CSS formatting rules from the IDMX 225 Style Guide.

## Steps

1. Download the clone of your completed Project 1 repo.
2. Copy your P1 folders and files into this repo.
3. Commit your repo and `push` it to GitHub.
4. You are going to add a footer that looks like the header. Add a semantic HTML footer (with class footer) element to your HTML code. See the header element that is already there for an example. The footer has to go in the correct spot in the index.html file. It goes in right after the main close tag and before the close html tag.


`<footer class="footer"> footer stuff goes here </footer>`

5. Note: You should regularly commit and push to your master branch.
6. Add a copyright statement inside your footer using your name. See your text to get the code for a copyright symbol.
7. Look at the picture in this repo's design folder. You are going to make changes to the CSS to copy how the footer looks in the picture.

8. One of the first things to change is the background color of the header and footer.
9. Go to [Coolors](https://coolors.co/app) and keep hitting space bar until you see a color you like.
10. Select _ONE_ fairly dark color (your choice) and take note of its hex code. 
11. Change your CSS so that the "hero", "iama" and the "footer" classes are your chosen color theme.
12. You are going to replace the current font with a different one. Notice the line in the head that says:

`<link href='https://fonts.googleapis.com/css?family=Source+Sans+Pro:300,400,600,700' rel='stylesheet' type='text/css'>`

and in `styles.css`


13. Search for "Google Fonts" on the Internet. Once in that page, use the top-right search for `Fira Sans`. Select `Fira Sans` and and to the selection font weights 400 and 600 (in the Customize tab).
14. Copy and paste the 2 links Google gives you (in the Embed tab).
- Replace the link that goes into the head element of `index.html`.
- Replace the `font-family` rule in the `styles.css` file.
15. From the design picture, note the look of the text in the footer matches the text of the person's name in the header. You should add css that does the same for your footer.

### Before Calling It Finished
* Validate and correct your html code and your CSS code. Check the formatting, making sure everything is properly nested. [CSS Validation](https://jigsaw.w3.org/css-validator/) and [HTML Validation](https://jigsaw.w3.org/css-validator/)
* Edit your `README.md` file changing it to be a `README.md` for P2. Delete anything to do with P1 and add a desccription for P2.
* Commit all changes to GitHub. 

