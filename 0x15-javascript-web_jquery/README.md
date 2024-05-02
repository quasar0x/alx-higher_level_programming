DOM Manipulation with JavaScript and jQuery
This project serves as a learning exercise for manipulating the Document Object Model (DOM) using JavaScript and jQuery. It includes various tasks aimed at practicing DOM manipulation techniques before implementing them into larger projects.

Tests ✅
tests: This directory contains HTML files for testing DOM manipulation scripts.
Tasks 📃
0. No jQuery
0-script.js: JavaScript script that updates the text color of the HTML HEADER tag to red (#ff0) using document.querySelector.
1. With jQuery
1-script.js: JavaScript script that updates the text color of the HTML HEADER tag to red (#ff0) using jQuery.
2. Click and turn red
2-script.js: JavaScript script that turns the text color of the HTML HEADER tag to red (#ff0) when the user clicks on the DIV#red_header tag.
3. Add .red class
3-script.js: JavaScript script that adds the .red class to the HTML HEADER tag when the user clicks on the DIV#red_header tag.
4. Toggle classes
4-script.js: JavaScript script that toggles the class of the HTML HEADER tag between .red and .green when the user clicks on the DIV#red_header tag.
5. List of elements
5-script.js: JavaScript script that adds a <LI> element to a list when the user clicks on the DIV#add_item tag. It appends the element <li>Item</li> to UL.my_list.
6. Change the text
6-script.js: JavaScript script that updates the text of the HTML HEADER tag to "New Header!!!" when the user clicks on the DIV#update_header tag.
7. Star wars character
7-script.js: JavaScript script that fetches and displays the name of a Star Wars character from the Star Wars API https://swapi.co/api/people/5/?format=json in the HTML DIV#character tag.
8. Star Wars movies
8-script.js: JavaScript script that fetches and lists all movie titles from the Star Wars API https://swapi.co/api/films/?format=json. It displays the titles in the HTML UL#list_movies tag.
9. Say Hello!
9-script.js: JavaScript script that fetches and displays the translation of "Hello" in French using the API https://fourtonfish.com/hellosalut/?lang=fr. It shows the translation in the HTML DIV#hello tag.
10. No jQuery - document loaded
100-script.js: JavaScript script that updates the text color of the HTML HEADER tag to red (#ff0) using document.querySelector. It executes when imported in the HEAD tag.
11. List, add, remove
101-script.js: JavaScript script that adds, removes, and clears LI elements from a list based on user click input. It adds a new element when the user clicks DIV#add_item, removes the last element when the user clicks DIV#remove_item, and clears all elements when the user clicks DIV#clear_list. It works when imported in the HEAD tag.
12. Say hello to everybody!
102-script.js: JavaScript script that fetches and displays the translation of "Hello" in a given language using the API https://www.fourtonfish.com/hellosalut/hello/. It fetches the translation for the language entered in the HTML INPUT#language_code, and displays the translation in the HTML DIV#hello. It works when imported in the HEAD tag.
13. And press ENTER
103-script.js: JavaScript script that fetches and displays the translation of "Hello" in a given language using the API https://www.fourtonfish.com/hellosalut/hello/. It works similar to 102-script.js but also fetches the translation when the user presses ENTER when hovering over the INPUT#language_code tag.