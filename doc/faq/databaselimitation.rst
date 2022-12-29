.. _database_limitation:

Database limitation
====================

Toolmap uses an embedded database to store its projects. Since version 4.0 of ToolMap the MariaDB database is used in replacement of MySQL. Because, the embedded version of MySQL is not maintained any more.

MariaDB brings a lot of performance improvement but does not support the opening of projects located in different directories without restarting the program as shown in the image below.

.. image:: img/database_folder.svg

#. ToolMap can open the different projects without restarting
#. ToolMap must restart to open the different projects