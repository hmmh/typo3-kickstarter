TYPO3 Kickstarter
=================

This is a early first thrown for a quickly kick to start the development with local PHP and Sqlite.

- No need of a server instance.
- No need of a database instance.
- No need of secure connections.

Just feel free to copy databases and switch to your PHP versions easily.


---

Have a look on [PHPBrew](https://github.com/phpbrew/phpbrew).


Requirements
------------

Applications:

- PHP from 7.2
- Graphicksmagick from 1.3
- ImageMagick from 7.0


PHP Extensions:

- ext-json
- ext-pcre
- ext-PDO
- ext-session
- ext-sqlite3
- ext-tokenizer
- ext-xml
- ext-gd


To start up
-----------

Just execute this small kick:

    $ composer install
    
    ...
    
    $ composer serve
    
Now you can open your browser and start with:

- Backend: https://127.0.0.1:8080/typo3/
- Frontend: https://127.0.0.1:8080/


Backend:
--------

- Username: admin
- Password: Secret!234

Installed modules:

- Backend user

---

Happy prototyping and testing!
