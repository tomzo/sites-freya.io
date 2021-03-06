Routers
=======

The :doc:`/reference/core/index` library, along with the :doc:`/reference/types/index` and :doc:`/reference/optics/index` libraries, allow for the creation of powerful handlers for HTTP requests, but they don't provide support for routing requests to specific handlers.

Routers are used to solve this problem, and allow for the aggregation of multiple handlers in to a more complex application. Freya allows for the possibility of multiple different implementations of routing, to support differing requirements. Currently Freya includes one router, based on URI Templates.

* :doc:`uri-template/index` -- a router which efficiently uses URI Templates to dispatch HTTP requests to handlers, and exposing the matched data as strongly typed URI Template data types.

.. toctree::
   :hidden:

   uri-template/index
