=========
solcast-pvsolar
=========

| |Build Status| |pypi|




Solcast API

Client library for interacting with the Solcast API

Basic Usage
-----------

Get Forecasts
~~~~~~~~~~~~~

.. code-block:: python

    from pysolcast.rooftop import RooftopSite
    
    site = RooftopSite(api_key, resource_id)
    forecasts = site.get_forecasts()



.. |Build Status| image:: https://github.com/mcaulifn/solcast/workflows/Publish/badge.svg
   :target: https://github.com/oziee/solcast-pvsolar

.. |pypi| image:: https://badge.fury.io/py/pysolcast.svg
    :target: https://badge.fury.io/py/pysolcast

