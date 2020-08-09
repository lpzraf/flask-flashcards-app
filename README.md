## Flashcards Application with Python Flask

1. Set in the terminal 'export FLASK_APP=flash-cards.py' <--tells Flask where the application is located.
2. Set in the termninal 'export FLASK_DEV=development' <-- enables dev features like the debugger and the automatic reloads.
3. Run the app while in the directory with 'flask run'.

Note: do not run the dev server in production due to security reasons.

### Model-Template-View
Or MVC(Model-View-Controller) outside Python.

Model (Data) - usually from a DB but I'm using a json file with data.  
Template (Presentation) - generates the html using Jinja2.  
Views (Behavior) - Python functions mapped to urls.