# Articles

A simple python app using Flask and MySQL to create a session-based newspaper app. As it is, anyone can create an account and post articles.

If using this for your own site I'd suggest only allowing the site admin to create users and letting users change their password using an UPDATE form (like the edit article route).

If pushing to Heroku you'll need to setup CloudDB and a table structure to match what the routes are looking for/posting to.
