couchapp-pouchdb-getting-started-todo
============================

The source repository for the getting started tutorial for PouchDB, packed inside a Couchapp

This couchapp is ready to be deployed on a CouchDB server.
### Get started now:

    $ sudo apt install couchdb python-dev python-pip
    $ pip install --user couchapp
    $ git clone git@github.com:kapcom01/couchapp-pouchdb-getting-started-todo.git
    $ cd couchapp-pouchdb-getting-started-todo
    $ couchapp push test-todo-db


You should see something like this:

	2017-01-15 18:26:19 [INFO] Visit your CouchApp here:
	http://localhost:5984/testdb/_design/couchapp-pouchdb-getting-started-todo/index.html

Gongratulations!