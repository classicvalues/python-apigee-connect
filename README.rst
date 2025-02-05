Python Client for Apigee Connect
================================

|ga| |pypi| |versions|

`Apigee Connect`_: allows the Apigee hybrid management plane to connect securely to the MART 
service in the runtime plane without requiring you to expose the MART endpoint on the internet. 
If you use Apigee Connect, you do not need to configure the MART ingress gateway with a host alias 
and an authorized DNS certificate.

- `Client Library Documentation`_
- `Product Documentation`_

.. |ga| image:: https://img.shields.io/badge/support-ga-gold.svg
   :target: https://github.com/googleapis/google-cloud-python/blob/main/README.rst#ga-support
.. |pypi| image:: https://img.shields.io/pypi/v/google-cloud-apigee-connect.svg
   :target: https://pypi.org/project/google-cloud-apigee-connect/
.. |versions| image:: https://img.shields.io/pypi/pyversions/google-cloud-apigee-connect.svg
   :target: https://pypi.org/project/google-cloud-apigee-connect/
.. _Apigee Connect: https://cloud.google.com/apigee/docs/hybrid/v1.4/apigee-connect
.. _Client Library Documentation: https://cloud.google.com/python/docs/reference/apigeeconnect/latest
.. _Product Documentation:  https://cloud.google.com/apigee/docs/hybrid/v1.4/apigee-connect

Quick Start
-----------

In order to use this library, you first need to go through the following steps:

1. `Select or create a Cloud Platform project.`_
2. `Enable billing for your project.`_
3. `Enable the Apigee Connect API.`_
4. `Setup Authentication.`_

.. _Select or create a Cloud Platform project.: https://console.cloud.google.com/project
.. _Enable billing for your project.: https://cloud.google.com/billing/docs/how-to/modify-project#enable_billing_for_a_project
.. _Enable the Apigee Connect API.:  https://cloud.google.com/apigee/docs/hybrid/v1.4/apigee-connect#add-apigee-connect-to-the-hybrid-runtime
.. _Setup Authentication.: https://googleapis.dev/python/google-api-core/latest/auth.html

Installation
~~~~~~~~~~~~

Install this library in a `virtualenv`_ using pip. `virtualenv`_ is a tool to
create isolated Python environments. The basic problem it addresses is one of
dependencies and versions, and indirectly permissions.

With `virtualenv`_, it's possible to install this library without needing system
install permissions, and without clashing with the installed system
dependencies.

.. _`virtualenv`: https://virtualenv.pypa.io/en/latest/


Mac/Linux
^^^^^^^^^

.. code-block:: console

    pip install virtualenv
    virtualenv <your-env>
    source <your-env>/bin/activate
    <your-env>/bin/pip install google-cloud-apigee-connect


Windows
^^^^^^^

.. code-block:: console

    pip install virtualenv
    virtualenv <your-env>
    <your-env>\Scripts\activate
    <your-env>\Scripts\pip.exe install google-cloud-apigee-connect

Next Steps
~~~~~~~~~~

-  Read the `Client Library Documentation`_ for Apigee Connect
   to see other available methods on the client.
-  Read the `Apigee Connect Product documentation`_ to learn
   more about the product and see How-to Guides.
-  View this `README`_ to see the full list of Cloud
   APIs that we cover.

.. _Apigee Connect Product documentation:  https://cloud.google.com/apigee/docs/hybrid/v1.4/apigee-connect
.. _README: https://github.com/googleapis/google-cloud-python/blob/main/README.rst