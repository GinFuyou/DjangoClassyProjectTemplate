# -*- coding: utf-8 -*-
"""{{ project_name }} URL Configuration

The `urlpatterns` list routes URLs to views. For more information please see:
    https://docs.djangoproject.com/en/{{ docs_version }}/topics/http/urls/
"""

from django.conf.urls import url, include
from django.contrib import admin
from django.conf import settings
# from django.conf.urls.i18n import i18n_patterns
# from django.views.generic.base import TemplateView

from django.urls import path

urlpatterns = [
    path('', include('core.urls')),
    path('admin/', admin.site.urls),
]

#if settings.DEBUG :
#    import debug_toolbar
#    urlpatterns.append(path('dj-dt/', include(debug_toolbar.urls)),)
