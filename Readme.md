TYPO3 Kickstarter
=================

This is an early first throw for a quick start to development with local PHP and SQLite.

- No need of a server instance.
- No need of a database instance.
- No need of secure connections.

Just feel free to copy databases and switch to your PHP versions easily.


---

Just have a look on [PHPBrew](https://github.com/phpbrew/phpbrew).


Requirements
------------

Applications:

- PHP from 7.2
- Optional: Graphicksmagick from 1.3 or ImageMagick from 7.0


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

Install the new project:

    $ composer create-project hmmh/typo3-kickstarter t3kick --no-scripts

The `--no-scripts` flag is required because after the project is created, the official TYPO3 command events are
executed first, and it breaks with a missing database connection.

Then execute this small steps (dependencies are already installed):

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
