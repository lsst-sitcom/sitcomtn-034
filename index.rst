..
  Technote content.

  See https://developer.lsst.io/restructuredtext/style.html
  for a guide to reStructuredText writing.

  Do not put the title, authors or other metadata in this document;
  those are automatically added.

  Use the following syntax for sections:

  Sections
  ========

  and

  Subsections
  -----------

  and

  Subsubsections
  ^^^^^^^^^^^^^^

  To add images, add the image file (png, svg or jpeg preferred) to the
  _static/ directory. The reST syntax for adding the image is

  .. figure:: /_static/filename.ext
     :name: fig-label

     Caption text.

   Run: ``make html`` and ``open _build/html/index.html`` to preview your work.
   See the README at https://github.com/lsst-sqre/lsst-technote-bootstrap or
   this repo's README for more info.

   Feel free to delete this instructional comment.

:tocdepth: 1

.. Please do not modify tocdepth; will be fixed when a new Sphinx theme is shipped.

.. sectnum::

.. TODO: Delete the note below before merging new content to the main branch.

Introduction
============

This tech note compiles all work done by the SIT-Com image quality team.

Team Description
================

The team description can be found at https://sitcomtn-017.lsst.io/

Image Quality Team Glossary
===========================

Glossary providing definitions for different image quality related terms, such as 'seeing,' as they are used in reports by this team.
https://confluence.lsstcorp.org/pages/viewpage.action?spaceKey=LSSTCOM&title=proposed+glossary+for+image+quality

Aux Tel Image Quality Budget Table
==================================

Table with measured AuxTel image quality values and analysis methods: https://confluence.lsstcorp.org/display/LSSTCOM/image+quality+budget+table

Operations Plan
===============

Operations plan for optimizing image quality: https://sitcomtn-036.lsst.io

Aux Tel Donut Analysis
======================

A donut analysis technique that can be used for wavefront sensor verification: https://sitcomtn-027.lsst.io

A method to estimate uncorrected wavefront errors in AuxTel with the donut analysis: https://sitcomtn-042.lsst.io/


Aux Tel Focus Model
===================

Study of the Aux Tel focus drift as a function of temperature: https://sitcomtn-028.lsst.io/

Aux Tel Tracking analysis
=========================

An analysis of the Nov 2021 Aux Tel run: https://sitcomtn-021.lsst.io/

Aux Tel Fan Analysis
====================

Measurements of AuxTel vibrations as the AuxTel fan is turned on, with the dome slit open: https://sitcomtn-051.lsst.io/




.. Add content here.
.. Do not include the document title (it's automatically added from metadata.yaml).

.. .. rubric:: References

.. Make in-text citations with: :cite:`bibkey`.

.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
..    :style: lsst_aa
