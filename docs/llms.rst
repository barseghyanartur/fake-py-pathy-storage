Project source-tree
===================

Below is the layout of the project (to 10 levels), followed by
the contents of each key file.

.. code-block:: text
   :caption: Project directory layout

   fake-py-pathy-storage/
   ├── docs
   │   ├── conf.py
   │   ├── contributor_guidelines.rst
   │   ├── index.rst
   │   ├── package.rst
   │   ├── pathy_storage.rst
   │   └── pathy_storage.tests.rst
   ├── fakepy
   │   └── pathy_storage
   │       ├── tests
   │       │   ├── __init__.py
   │       │   ├── data.py
   │       │   └── test_storages.py
   │       ├── __init__.py
   │       ├── aws_s3.py
   │       ├── azure_cloud_storage.py
   │       ├── cloud.py
   │       ├── google_cloud_storage.py
   │       └── helpers.py
   ├── conftest.py
   ├── CONTRIBUTING.rst
   ├── Makefile
   ├── pyproject.toml
   └── README.rst

README.rst
----------

.. literalinclude:: ../README.rst
   :language: rst
   :caption: README.rst

CONTRIBUTING.rst
----------------

.. literalinclude:: ../CONTRIBUTING.rst
   :language: rst
   :caption: CONTRIBUTING.rst

conftest.py
-----------

.. literalinclude:: ../conftest.py
   :language: python
   :caption: conftest.py

docs/conf.py
------------

.. literalinclude:: conf.py
   :language: python
   :caption: docs/conf.py

docs/contributor_guidelines.rst
-------------------------------

.. literalinclude:: contributor_guidelines.rst
   :language: rst
   :caption: docs/contributor_guidelines.rst

docs/index.rst
--------------

.. literalinclude:: index.rst
   :language: rst
   :caption: docs/index.rst

docs/package.rst
----------------

.. literalinclude:: package.rst
   :language: rst
   :caption: docs/package.rst

docs/pathy_storage.rst
----------------------

.. literalinclude:: pathy_storage.rst
   :language: rst
   :caption: docs/pathy_storage.rst

docs/pathy_storage.tests.rst
----------------------------

.. literalinclude:: pathy_storage.tests.rst
   :language: rst
   :caption: docs/pathy_storage.tests.rst

fakepy/pathy_storage/__init__.py
--------------------------------

.. literalinclude:: ../fakepy/pathy_storage/__init__.py
   :language: python
   :caption: fakepy/pathy_storage/__init__.py

fakepy/pathy_storage/aws_s3.py
------------------------------

.. literalinclude:: ../fakepy/pathy_storage/aws_s3.py
   :language: python
   :caption: fakepy/pathy_storage/aws_s3.py

fakepy/pathy_storage/azure_cloud_storage.py
-------------------------------------------

.. literalinclude:: ../fakepy/pathy_storage/azure_cloud_storage.py
   :language: python
   :caption: fakepy/pathy_storage/azure_cloud_storage.py

fakepy/pathy_storage/cloud.py
-----------------------------

.. literalinclude:: ../fakepy/pathy_storage/cloud.py
   :language: python
   :caption: fakepy/pathy_storage/cloud.py

fakepy/pathy_storage/google_cloud_storage.py
--------------------------------------------

.. literalinclude:: ../fakepy/pathy_storage/google_cloud_storage.py
   :language: python
   :caption: fakepy/pathy_storage/google_cloud_storage.py

fakepy/pathy_storage/helpers.py
-------------------------------

.. literalinclude:: ../fakepy/pathy_storage/helpers.py
   :language: python
   :caption: fakepy/pathy_storage/helpers.py

fakepy/pathy_storage/tests/__init__.py
--------------------------------------

.. literalinclude:: ../fakepy/pathy_storage/tests/__init__.py
   :language: python
   :caption: fakepy/pathy_storage/tests/__init__.py

fakepy/pathy_storage/tests/data.py
----------------------------------

.. literalinclude:: ../fakepy/pathy_storage/tests/data.py
   :language: python
   :caption: fakepy/pathy_storage/tests/data.py

fakepy/pathy_storage/tests/test_storages.py
-------------------------------------------

.. literalinclude:: ../fakepy/pathy_storage/tests/test_storages.py
   :language: python
   :caption: fakepy/pathy_storage/tests/test_storages.py

pyproject.toml
--------------

.. literalinclude:: ../pyproject.toml
   :language: toml
   :caption: pyproject.toml
