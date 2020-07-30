# Wiki
This is Wikipedia-like online encyclopedia web application that consists of a number of encyclopedia entries on various topics. Through this application a user can create, search and read number of encyclopedia entries on various topics published by other users.

## Technologies used
- Python
- Django
- Javascript
- HTML5
- Css3
- Bootstrap4
- Markdown2
- Sqlite3

## Specification
This application fulfill the following features:
1. **Entry Page::**
- Visiting /wiki/TITLE, where TITLE is the title of an encyclopedia entry, will render a page that displays the contents of that encyclopedia entry. 
- If the entry does exist, the user will be presented with a page that displays the content of the entry. The title of the page should include the name of the entry.

2. **Index Page:**
- On the index.html, instead of merely listing the names of all pages in the encyclopedia, user can click on any entry name to be taken directly to that entry page.

3. **Search:**
-  User can type a query into the search box in the sidebar to search for an encyclopedia entry. 
- If the query matches the name of an encyclopedia entry, the user will be redirected to that entry’s page.
- If the query does not match the name of an encyclopedia entry, the user will instead be taken to a search results page that displays a list of all encyclopedia entries that have the query as a substring. For example, if the search query were Py, then Python should appear in the search results.
- Clicking on any of the entry names on the search results page should take the user to that entry’s page.

4. **New Page:**
- Clicking “Create New Page” in the sidebar will take the user to a page where they can create a new encyclopedia entry. 
- When the page is saved, if an encyclopedia entry already exists with the provided title, the user will be presented with an error message.
- Otherwise, the encyclopedia entry will be saved to disk, and the user should be taken to the new entry’s page.

5. **Edit Page:**
- On each entry page, the user is able to click a link to be taken to a page where the user can edit that entry’s Markdown content in a textarea.
- The user is be able to click a button to save the changes made to the entry. Once the entry is saved, the user will be redirected back to that entry’s page.

6. **Random Page:**
- Clicking “Random Page” in the sidebar will take user to a random encyclopedia entry.

7. **Markdown to HTML Conversion:**
- On each entry’s page, any Markdown content in the entry file will be converted to HTML before being displayed to the user.
