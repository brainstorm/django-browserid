API
===

Template Helpers
----------------

.. autofunction:: django_browserid.helpers.browserid_info()

.. autofunction:: django_browserid.helpers.browserid_login

.. autofunction:: django_browserid.helpers.browserid_logout

.. autofunction:: django_browserid.helpers.browserid_js


Verification
------------

.. autoclass:: django_browserid.RemoteVerifier
   :members: verify

.. autoclass:: django_browserid.base.MockVerifier
   :members: __init__, verify

.. autoclass:: django_browserid.base.VerificationResult
   :members: expires

.. autofunction:: django_browserid.get_audience


Views
-----

.. autoclass:: django_browserid.views.Verify
   :members:
   :show-inheritance:


Signals
-------

.. automodule:: django_browserid.signals
   :members:


Exceptions
----------

.. autoexception:: django_browserid.base.BrowserIDException
   :members:
