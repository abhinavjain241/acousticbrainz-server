Web API
=======

AcousticBrianz server provides a Web API for getting and submitting data.

**Base URL**: ``https://acousticbrainz.org``

Endpoint Reference
------------------

Core data
^^^^^^^^^

.. autoflask:: webserver:create_app_sphinx()
   :blueprints: api_v1_core
   :include-empty-docstring:
   :undoc-static:

