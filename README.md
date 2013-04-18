pubnub
======

Installation
------------

Install with Composer
~~~~~~~~~~~~~~~~~~~~~

If you're using `Composer <https://github.com/composer/composer>`_ to manage
dependencies, you can get the latest version off the master branch:

::

    {
        "require": {
            "gektor1/pubnub": "dev-master"
        }
    }


Install source from GitHub
~~~~~~~~~~~~~~~~~~~~~~~~~~

To install the source code:

::

    $ git clone git://github.com/gektor1/pubnub.git

And including it using the autoloader:

::

    require_once '/path/to/Pubnub/library/Pubnub.php';
    Raven_Autoloader::register();

Or, if you're using `Composer <https://github.com/composer/composer>`_:

::

    require_once 'vendor/autoload.php';
    