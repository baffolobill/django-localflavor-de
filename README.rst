=====================
django_localflavor_de
=====================

Country-specific Django helpers for Germany.

What's in the Germany localflavor?
==================================

* DEIdentityCardNumberField: A form field that validates input as a German
  identity card number (Personalausweis_). Valid numbers have the format
  XXXXXXXXXXX-XXXXXXX-XXXXXXX-X, with no group consisting entirely of zeroes.

* DEZipCodeField: A form field that validates input as a German zip code.
  Valid codes consist of five digits.

* DEStateSelect: A ``Select`` widget that uses a list of German states as its
  choices.

.. _Personalausweis: http://de.wikipedia.org/wiki/Personalausweis

See the source code for full details.

About localflavors
==================

Django's "localflavor" packages offer additional functionality for particular
countries or cultures.

For example, these might include form fields for your country's postal codes,
phone number formats or government ID numbers.

This code used to live in Django proper -- in django.contrib.localflavor -- but
was separated into standalone packages in Django 1.5 to keep the framework's
core clean.

For a full list of available localflavors, see https://github.com/django/
