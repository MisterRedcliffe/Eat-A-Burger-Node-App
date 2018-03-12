# burger
Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.
It uses MySQL, Node, Express, Handlebars and a custom ORM. It also uses th MVC design pattern and uses Handlebars to generate the HTML.

# How the program works

From the command line you can run the following command.
1. `node server.js` and then open a browser an type localhost:3000

2. Running this application takes you to the main page and you can then add burgers to the list of burgers you would like to eat.

3. Whenever a user submits a burger's name, the app will display the burger on the left side of the page -- waiting to be devoured.

4. Each burger in the waiting area also has a `Devour` button. When the user clicks it, the burger will move to the right side of the page.

5. The app will store every burger in a database, whether devoured or not.

# npm modules used
1. `express`
2. `body-parser`
3. `mysql`
4. `express-handlebars`
