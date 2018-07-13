# item-catalog-project
Udacity project.  Item catalog website with db CRUD and oauth FB and Google login.


## Testing:

1. Open terminal to folder location of cloned repo.
2. Run database_setup_catalog.py: `python database_setup_catalog.py`
3. Run database_management.py: `python database_management.py`
4. Run catalog.py to start web app: `python catalog.py`

## Expected functionality:
* Users can login / logout with FB or Google Plus sign in.
* Users cannot Get or Post New, Edit, or Delete pages without being signed in.
* Users cannot Get or Post Edit or Delete game items without being the original creators of the game item.
* Logged in users can create new game items.
