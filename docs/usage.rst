=====
Usage
=====

To use Django Frontend Presets in a project, add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'django_frontend_presets.apps.DjangoFrontendPresetsConfig',
        ...
    )

Add Django Frontend Presets's URL patterns:

.. code-block:: python

    from django_frontend_presets import urls as django_frontend_presets_urls


    urlpatterns = [
        ...
        url(r'^', include(django_frontend_presets_urls)),
        ...
    ]
