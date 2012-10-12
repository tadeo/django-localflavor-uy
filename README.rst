=====================
django_localflavor_uy
=====================

Country-specific Django helpers for Uruguay.

What's in the Uruguay localflavor?
==================================

* forms.UYCIField: A field that validates Uruguayan 'Cedula de identidad' (CI)
  numbers.

* forms.UYDepartamentSelect: A ``Select`` widget that uses a list of Uruguayan
  departments as its choices.

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
