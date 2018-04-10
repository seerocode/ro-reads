# ro-reads
I have a bookcase and several shelves in my bedroom linen closet (yep) crammed with books I've collected over the years. I carry around a nook now (caring for a baby and train rides tends to make flipping pages difficult) but I often end up purchasing physical copies of books I enjoyed reading digitally so I can read them again later at home. 

Alas, I live in an apartment and there isn't much space to keep buying books so I'm employing a one-in-one-out solution until it kills me to part with any other books. To do this, I need a portable way to catalog the books I (and my husband) own. There are plenty of solutions out there to do this but this seemed like a good opportunity for me to learn and make something useful for myself. 

Ro Reads was born! Well, it's still cooking. Stick with me here.

## The Idea
Create a visual web app representing the books my husband and I collectively own; categorized by genre, author, title, and book type. We have anything from board books, textbooks, magazines, comic books, paperback and hardcover books, and I'm pretty sure there are some manuals and binders in there somewhere. 

The visualization will be the spines of a book facing out toward the screen with the title of a book on a spine. I will be feeding json data into Vue app from a postgresql database (building an API for this). When a spine is clicked on, the front cover of the book will come up on the screen with its description (fed from Goodreads API). 

Visualization can be toggled to card view instead to browse books by cover. Option to randomly pick a book from the shelf will also be available.

In the future, would like to include add/edit/delete options from the app that communicates with the database so book info can be edited directly from the app.

Tasks:
- [ ] Install postgresql
