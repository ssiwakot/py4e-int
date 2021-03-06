Python and Web Services
:::::::::::::::::::::::::::::::::::::::::::
Once it became easy to retrieve documents and parse documents over HTTP
using programs, it did not take long to develop an approach where we
started producing documents that were specifically designed to be
consumed by other programs (i.e., not HTML to be displayed in a
browser).

There are two common formats that we use when exchanging data across the
web. eXtensible Markup Language (XML) has been in use for a very
long time and is best suited for exchanging document-style data. When
programs just want to exchange dictionaries, lists, or other internal
information with each other, they use JavaScript Object Notation (JSON)
(see `www.json.org <http://www.json.org>`_\ ). We will look at both formats.

.. toctree::
    :caption: Using Web Services
    :maxdepth: 3

    13-xml.rst
    13-parsingXML.rst
    13-loopingNodes.rst
    13-JSON.rst
    13-parsingJSON.rst
    13-applicationProg.rst
    13-securityAPI.rst
    13-glossary.rst
    Exercises.rst
    13-MixedupCode.rst
    13-writeCode.rst
    13-google.rst
    13-twitter.rst
