..  Title: MyMagento
..  Description: A Python package that wraps and extends the Magento 2 REST API
..  Author: TDKorn

.. |Tip| replace:: 💡 **Tip**
.. |RTD| replace:: **Explore the docs »**
.. _RTD: https://my-magento.readthedocs.io/en/latest/
.. |api_endpoint| replace:: API endpoint
.. _api_endpoint: https://adobe-commerce.redoc.ly/2.3.7-admin/
.. Classes
.. |.Client| replace:: Client
.. _.Client: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/clients.py#L13-L378
.. |.Model| replace:: Model
.. _.Model: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/models/model.py#L13-L241
.. |.SearchQuery| replace:: SearchQuery
.. _.SearchQuery: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/search.py#L14-L313
.. |.Order| replace:: Order
.. _.Order: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/models/order.py#L12-L182
.. |.Product| replace:: Product
.. _.Product: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/models/product.py#L12-L388
.. |.APIResponse| replace:: APIResponse
.. _.APIResponse: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/models/model.py#L244-L286
.. |.Category| replace:: Category
.. _.Category: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/models/category.py#L12-L146
.. |.MediaEntry| replace:: MediaEntry
.. _.MediaEntry: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/models/product.py#L391-L556
.. Functions and Methods
.. |.get_api| replace:: get_api()
.. _.get_api: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/__init__.py#L18-L41
.. |.authenticate| replace:: authenticate()
.. _.authenticate: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/clients.py#L227-L254
.. |.execute| replace:: execute()
.. _.execute: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/search.py#L130-L141
.. |.search| replace:: search()
.. _.search: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/clients.py#L144-L167
.. |.by_id| replace:: by_id()
.. _.by_id: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/search.py#L143-L158
.. |.by_list| replace:: by_list()
.. _.by_list: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/search.py#L160-L188
.. |.get| replace:: get()
.. _.get: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/clients.py#L199-L204
.. |.url_for| replace:: url_for()
.. _.url_for: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/clients.py#L115-L140
.. |.post| replace:: post()
.. _.post: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/clients.py#L204-L210
.. |.put| replace:: put()
.. _.put: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/clients.py#L212-L218
.. |.delete| replace:: delete()
.. _.delete: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/clients.py#L220-L225
.. |.add_criteria| replace:: add_criteria()
.. _.add_criteria: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/search.py#L44-L111
.. |.restrict_fields| replace:: restrict_fields()
.. _.restrict_fields: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/search.py#L113-L128
.. |.until| replace:: until()
.. _.until: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/search.py#L216-L227
.. |.since| replace:: since()
.. _.since: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/search.py#L190-L214
.. |.Model.refresh| replace:: Model.refresh()
.. _.Model.refresh: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/models/model.py#L131-L165
.. |.set_alt_text| replace:: set_alt_text()
.. _.set_alt_text: https://github.com/TDKorn/my-magento/blob/v2.1.1/magento/models/product.py#L502-L512
.. |.ProductSearch.by_sku| replace:: by_sku()
.. _.ProductSearch.by_sku: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/search.py#L690-L695
.. Class Variables and Instance Attributes
.. |.ACCESS_TOKEN| replace:: ACCESS_TOKEN
.. _.ACCESS_TOKEN: https://github.com/TDKorn/my-magento/blob/v2.1.1/magento/clients.py#L72
.. |.USER_CREDENTIALS| replace:: USER_CREDENTIALS
.. _.USER_CREDENTIALS: https://github.com/TDKorn/my-magento/blob/v2.1.1/magento/clients.py#L67-L70
.. |.Client.scope| replace:: Client.scope
.. _.Client.scope: https://github.com/TDKorn/my-magento/blob/main/magento/clients.py#L75-L76
.. |.scope| replace:: scope
.. _.scope: https://github.com/TDKorn/my-magento/blob/main/magento/clients.py#L75-L76
.. |.result| replace:: result
.. _.result: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/search.py#L229-L241
.. |.views| replace:: views
.. _.views: https://github.com/tdkorn/my-magento/blob/v2.1.1/magento/clients.py#L410-L413


MyMagento🛒
---------------

.. image:: https://i.imgur.com/dkCWWYn.png
   :alt: Magento Logo
   :align: center
   :width: 200
   :height: 175

A Python package that wraps and extends the Magento 2 REST API

|RTD|_

|

.. image:: https://img.shields.io/pypi/v/my-magento?color=eb5202
   :target: https://pypi.org/project/my-magento/
   :alt: PyPI Version

.. image:: https://img.shields.io/badge/GitHub-my--magento-4f1abc
   :target: https://github.com/tdkorn/my-magento
   :alt: GitHub Repository

.. image:: https://static.pepy.tech/personalized-badge/my-magento?period=total&units=none&left_color=grey&right_color=blue&left_text=Downloads
    :target: https://pepy.tech/project/my-magento

.. image:: https://readthedocs.org/projects/my-magento/badge/?version=latest
    :target: https://my-magento.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

|

About MyMagento
~~~~~~~~~~~~~~~~~~~~

.. |note| replace:: 📝

+-------------------------------------------------------------+
| |note| What's MyMagento?                                    |
+=============================================================+
|  ``MyMagento`` is a highly interconnected package that      |
|  wraps and extends the Magento 2 REST API, providing a more |
|  intuitive and user-friendly interface to access and update |
|  your store                                                 |
+-------------------------------------------------------------+


MyMagento simplifies interaction with the Magento 2 REST API
=================================================================

If you've worked with the Magento 2 API, you'll know that not all endpoints are created equally.

``MyMagento`` aims to streamline your workflow by simplifying a
variety of commonly needed API operations.


Main Components
==================================

.. |comp| replace:: 💻
.. |mag| replace:: 🔍

+-------------------------------------------------------------+
| |comp| The |.Client|_                                       |
+=============================================================+
|  * Handles all API interactions                             |
|  * Supports multiple store views                            |
|  * Provides access to all other package components          |
+-------------------------------------------------------------+

+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+
| |mag| The |.SearchQuery|_ and Subclasses                                                                                                                        |
+=================================================================================================================================================================+
| * Intuitive interface for `Building Custom Search Queries <https://my-magento.readthedocs.io/en/latest/interact-with-api.html#custom-queries>`_                 |
| * Simplified creation of basic and advanced `searches using REST endpoints <https://developer.adobe.com/commerce/webapi/rest/use-rest/performing-searches/>`_   |
| * All predefined methods retrieve data using only 1-2 API requests                                                                                              |
+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+

+----------------------------------------------------------------------------+
| 🧠 The |.Model|_ Subclasses                                                |
+============================================================================+
| * Wrap all API responses in the package                                    |
| * Provide additional endpoint-specific methods to retrieve and update data |
+----------------------------------------------------------------------------+


Available Endpoints
======================

``MyMagento`` is compatible with every |api_endpoint|_

Endpoints are wrapped with a `Model <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/models/model.py#L13-L241>`_ and `SearchQuery <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/search.py#L14-L313>`_ subclass as follows:

+--------------------------+-------------------------------------+----------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------+
| **Endpoint**             | **Client Shortcut**                 |`SearchQuery <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/search.py#L14-L313>`_ **Subclass** |`Model <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/models/model.py#L13-L241>`_ **Subclass**   |
+==========================+=====================================+==========================================================================================================+============================================================================================================+
| ``orders``               | ``Client.orders``                   | `OrderSearch <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/search.py#L316-L411>`_            | `Order <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/models/order.py#L12-L182>`_               |
+--------------------------+-------------------------------------+----------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------+
| ``orders/items``         | ``Client.order_items``              | `OrderItemSearch <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/search.py#L414-L526>`_        | `OrderItem <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/models/order.py#L185-L292>`_          |
+--------------------------+-------------------------------------+----------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------+
| ``invoices``             | ``Client.invoices``                 | `InvoiceSearch <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/search.py#L529-L654>`_          | `Invoice <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/models/invoice.py#L11-L57>`_            |
+--------------------------+-------------------------------------+----------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------+
| ``products``             | ``Client.products``                 | `ProductSearch <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/search.py#L657-L744>`_          | `Product <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/models/product.py#L12-L388>`_           |
+--------------------------+-------------------------------------+----------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------+
| ``products/attributes``  | ``Client.product_attributes``       | `ProductAttributeSearch <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/search.py#L747-L775>`_ | `ProductAttribute <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/models/product.py#L559-L588>`_ |
+--------------------------+-------------------------------------+----------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------+
| ``categories``           | ``Client.categories``               | `CategorySearch <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/search.py#L778-L820>`_         | `Category <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/models/category.py#L12-L146>`_         |
+--------------------------+-------------------------------------+----------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------+
| ``endpoint``             | ``Client.search("endpoint")``       | `SearchQuery <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/search.py#L14-L313>`_             | `APIResponse <https://github.com/tdkorn/my-magento/blob/v2.1.0/magento/models/model.py#L244-L286>`_        |
+--------------------------+-------------------------------------+----------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------+

|

⚙ Installing MyMagento
~~~~~~~~~~~~~~~~~~~~~~~~~~

To install using ``pip``::

   pip install my-magento

Please note that ``MyMagento`` requires ``Python >= 3.10``

...

📚 Documentation
~~~~~~~~~~~~~~~~~~

Full documentation can be found on `ReadTheDocs <https://my-magento.readthedocs.io/en/latest/>`_


|

QuickStart: Login with MyMagento
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

``MyMagento`` uses the |.Client|_ class to handle all interactions with the API.

.. |login| replace:: Get a Magento 2 REST API Token With MyMagento
.. _login: https://my-magento.readthedocs.io/en/latest/examples/logging-in.html

+-------------------------------------------------------------+
| |Tip|                                                       |
+=============================================================+
| See |login|_ for full details on generating an access token |
+-------------------------------------------------------------+


Setting the Login Credentials
===================================

To generate an |.ACCESS_TOKEN|_ you'll need to |.authenticate|_ your |.USER_CREDENTIALS|_

Creating a |.Client|_ requires a ``domain``, ``username``, and ``password`` at minimum.


.. code-block:: python

   >>> domain = 'website.com'
   >>> username ='username'
   >>> password = 'password'


If you're using a local installation of Magento you'll need to set ``local=True``. Your domain should look like this:

.. code-block:: python

   >>> domain = '127.0.0.1/path/to/magento'


...

Getting a |.Client|_
=================================

Option 1: Initialize a |.Client|_ Directly
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. code-block:: python

      from magento import Client

      >>> api = Client(domain, username, password, **kwargs)


Option 2: Call |.get_api|_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. code-block:: python


      import magento

      >>> api = magento.get_api(**kwargs)

|.get_api|_ takes the same keyword arguments as the |.Client|_

* If the ``domain``, ``username``, or ``password`` are missing, it will attempt to use the following environment variables:


.. code-block:: python

   import os

   os.environ['MAGENTO_DOMAIN'] = domain
   os.environ['MAGENTO_USERNAME']= username
   os.environ['MAGENTO_PASSWORD']= password

...

Getting an |.ACCESS_TOKEN|_
=======================================

Unless you specify ``login=False``, the |.Client|_ will automatically call |.authenticate|_ once initialized


.. code-block:: python

   >>> api.authenticate()

   |[ MyMagento | website_username ]|:  Authenticating username on website.com...
   |[ MyMagento | website_username ]|:  Logged in to username

|


Performing a |.search|_
~~~~~~~~~~~~~~~~~~~~~~~~~

The |.search|_ method lets you |.execute|_ a query on any |api_endpoint|_

It creates a |.SearchQuery|_ for the endpoint,
allowing you to retrieve data for

* An individual item (ex. |.by_id|_)
* A list of items (ex. |.by_list|_)
* Any search criteria you desire (see `Building Custom Search Queries <https://my-magento.readthedocs.io/en/latest/interact-with-api.html#custom-queries>`_)

|



.. |doc| replace:: 📚

+----------------------------------------------------------------+
| |doc| From the Docs...                                         |
+================================================================+
|  *Client.search(endpoint)*                                     |
|   * Initializes and returns a |.SearchQuery|_                  |
|     corresponding to the specified ``endpoint``                |
|                                                                |
|  +-------------------------------------------------------+     |
|  | |note| Note                                           |     |
|  +=======================================================+     |
|  | Several endpoints have predefined |.SearchQuery|_ and |     |
|  | |.Model|_ subclasses                                  |     |
|  |                                                       |     |
|  | If a subclass hasn’t been defined for the             |     |
|  | ``endpoint`` yet, a general |.SearchQuery|_           |     |
|  | will be returned, which wraps the |.result|_ with     |     |
|  | |.APIResponse|_                                       |     |
|  +-------------------------------------------------------+     |
|                                                                |
|  **Parameters**                                                |
|    *endpoint* (``str``) – a valid Magento API search  endpoint |
|                                                                |
|  **Return type**                                               |
|    |.SearchQuery|_                                             |
+----------------------------------------------------------------+




Example: |.search|_ an endpoint |.by_id|_
===========================================

.. code-block:: python

    # Query the "invoices" endpoint (also: api.invoices)
    >>> api.search("invoices").by_id(1)

    <Magento Invoice: "#000000001"> for <Magento Order: "#000000001" placed on 2022-11-01 03:27:33>


|

Example: |.search|_ an endpoint |.by_list|_
==============================================

.. code-block:: python

    # Retrieve invoices from a list of invoice ids
    >>> ids = list(range(1,101))
    >>> api.invoices.by_list("entity_id", ids)

    [<Magento Invoice: "#000000001"> for <Magento Order: "#000000001" placed on 2022-11-01 03:27:33>, ...]

|

Search Results: The |.Model|_ Classes
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. |the_models| replace:: the ``magento.models`` subpackage
.. _the_models: models.html

The |.result|_ of any |.SearchQuery|_ will be parsed and wrapped by a
|.Model|_ class in |the_models|_.

These classes make the API response data easier to work with.

They also provide endpoint-specific methods to update store data and search for related items.

|

Example: Retrieving every |.Order|_  containing a |.Product|_
==================================================================

Let's retrieve a |.Product|_ using |.ProductSearch.by_sku|_

.. code-block:: python

   >>> product = api.products.by_sku("24-MB01")

We can search for orders containing this product as follows:

.. code-block:: python

    # Using the Product itself
    >>> product.get_orders()

    [<Magento Order: "#000000003" placed on 2022-12-21 08:09:33>, ... ]

    # Using an OrderSearch
    >>> api.orders.by_product(product)
    >>> api.orders.by_product_id(product.id)
    >>> api.orders.by_sku(product.sku)

    [<Magento Order: "#000000003" placed on 2022-12-21 08:09:33>, ... ]

|

Example: Retrieving some items related to a |.Category|_
=========================================================

.. code-block:: python

    # Get Category data
    >>> category = api.categories.by_name("Watches")
    >>> category.get_products()
    >>> category.get_invoices()

    [<Magento Product: 24-MG04>, <Magento Product: 24-MG01>, <Magento Product: 24-MG03>, ... ]
    [<Magento Invoice: "#000000004"> for <Magento Order: "#000000004" placed on 2022-11-14 03:27:33>, ... ]

|

Example: Updating the Thumbnail |.MediaEntry|_ of a |.Product|_
=================================================================

.. code-block:: python

    # Update product thumbnail label on specific store view
   >>> product.thumbnail.set_alt_text("bonjour", scope="FR")
   >>> print(product.thumbnail)

    <MediaEntry 3417 for <Magento Product: 24-MB01>: bonjour>

+----------------------------------------------------------------------------------------------------------------+
| |Tip| Set the Store Scope                                                                                      |
+================================================================================================================+
| If you have multiple store views, a ``store_code`` can be specified when retrieving/updating data              |
|                                                                                                                |
| * The |.Client.scope|_ is used by default - simply change it to switch store |.views|_                         |
| * Passing the ``scope`` keyword argument to |.url_for|_, |.Model.refresh|_,                                    |
|   and some Model update methods (like |.set_alt_text|_ above) will temporarily override the Client's scope     |
|                                                                                                                |
+----------------------------------------------------------------------------------------------------------------+


.. _Custom Queries:

Building Custom Search Queries
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

In addition to the predefined methods, you can also build your own queries

* Simply |.add_criteria|_, |.restrict_fields|_, and |.execute|_ the search
* The |.since|_ and |.until|_ methods allow you to further filter your query by date

.. |Example| replace:: 📄

+----------------------------------------------------------------------------------------------------------------+
| |Example| Example: Retrieve Orders Over $50 Placed Since the Start of 2023                                     |
+================================================================================================================+
|   .. code-block:: python                                                                                       |
|                                                                                                                |
|       >>> api.orders.add_criteria(                                                                             |
|       ...    field="grand_total",                                                                              |
|       ...    value="50",                                                                                       |
|       ...    condition="gt"                                                                                    |
|       ... ).since("2023-01-01").execute()                                                                      |
|                                                                                                                |
|       [<Magento Order: "#000000012" placed on 2023-01-02 05:19:55>, ... ]                                      |
|                                                                                                                |
+----------------------------------------------------------------------------------------------------------------+

Making Authorized Requests
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The |.Client|_ can be used to generate the |.url_for|_ any API endpoint,
including a store |.scope|_.

You can use this URL to make an authorized
|.get|_, |.post|_, |.put|_, or |.delete|_ request


Example: Making a |.get|_ Request
==================================

.. code-block:: python

 # Request the data for credit memo with id 7
 >>> url = api.url_for('creditmemo/7')
 >>> response = api.get(url)
 >>> print(response.json())

 {'adjustment': 1.5, 'adjustment_negative': 0, 'adjustment_positive': 1.5, 'base_adjustment': 1.5,  ... }


+--------------------------------------------------------------------------------------------------------------------+
| |note| Note                                                                                                        |
+====================================================================================================================+
|  Using a |.search|_ is simpler than making |.get|_                                                                 |
|  requests, since the |.result|_ is wrapped by                                                                      |
|  |.APIResponse|_ or other |.Model|_                                                                                |
|                                                                                                                    |
|   .. code-block:: python                                                                                           |
|                                                                                                                    |
|      # Retrieve credit memo with id 7 using a search                                                               |
|      >>> memo = api.search("creditmemo").by_id(7)                                                                  |
|      >>> print(memo.data)                                                                                          |
|      >>> print(memo)                                                                                               |
|                                                                                                                    |
|      {'adjustment': 1.5, 'adjustment_negative': 0, ...} 'adj|stment_positive': 1.5, 'base_adjustment': 1.5,  ... } |
|      <magento.models.model.APIResponse object at 0x0000 1BA42FD0FD1>                                               |
|                                                                                                                    |
+--------------------------------------------------------------------------------------------------------------------+
