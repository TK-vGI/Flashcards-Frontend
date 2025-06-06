# Flashcards-Frontend
#
If you are a beginner web developer, you need to know the basics of CSS and HTML. This project is great for those
who need somewhere to start. Your goal is to create a stylized page with flashcards, each containing a question on
one side and the answer on the other. You can choose any subject you want for your flashcards!

1. Setting up 1/3
•	Make an appropriate title using a <h1> element
•	Create a <div> with the question term for each of the nine cards.

First, you have to come up with the topic for your memory board. When selecting a theme to work with, remember that
your questions and answers shouldn’t be too long. Flashcards can be used as an educational tool for a wide variety
of tasks, from learning foreign words and scientific terms to memorizing the birthday dates of your new friends.
We chose to make geography themed flashcards that can help you memorize the countries' capitals. You can join us
with this idea using a list of national capitals on Wiki, or find another theme that interests you. 
Once you have chosen your topic of interest, edit the given HTML code. Add a suitable header for your memory-board
and nine <div> elements with question terms (in our case, countries). Don't forget to use a suitable tag for the
text inside <div> tags.
To preview your intermediate solution hover the mouse pointer over the HTML code to show the browser icons popup,
and click the icon that indicates the desired browser. Alternatively, select View | Open in Browser from the main
menu and then select the desired browser from the list.


2. Design 2/3
•	Make a set of square flash cards.
•	Set the background for the cards and the whole page using the CSS property background-image or background-color.
•	Position the cards using the CSS property grid or flex so they make a 3x3 table.
•	Set the fonts for the text.

You got to the most creative part of the project: design! It's time to work out what your web-page should look like.
You can make the decisions as you go, draw a tentative plan on a paper, or even use a design app like Figma. Feel free
to express your creativity, though there are some restrictions: since projects are about learning, restrictions are
necessary for educational and testing purposes.
Don't forget to add styling to the page and if you are using an external CSS file, make sure to add it to the src
folder and include a link to it in HTML.
First of all, let's design our flashcards. Set the size of divs with questions (notice: the cards are square),
add color to the background, round the corners if you want, and position the text inside. Then form a table from
the cards. We suggest using the following model of a page and CSS properties grid or flex.


3. On the Flip Side 3/3
•	Make the answer on the back side appear when the user hovers over the card. 

Your flashcards look beautiful, but something important is still missing. The advantage of flashcards is that they
contain answers on the back side so that you can check yourself. For each card, let's create the flip side with the
answer (in our case, the capital), which will appear when the user hovers the cursor over the card.
CSS animations are a lot of fun: they are beautiful and not too difficult to implement even for beginners.
CSS provides a great variety of effects that you can choose from, and the best option for flashcards is
probably flip animation.
To implement the effect, you can either go through our explanation,
watch the Youtube tutorial on flipping card animation, or do both: https://www.youtube.com/watch?v=SdC0DDdT_rM