To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

On the walkthrough tutorial, they are using codeanywhere, gitpod has additional terminal commands:
first:
- run `set_pg` command
- type `psql` to open the database table


then:
- run `python3`
- type, >>> `from taskmanager import app, db`
- type, >>> `app.app_context().push()`
- type, >>> `db_create_all()`