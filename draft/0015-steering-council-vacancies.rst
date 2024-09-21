====================================
DEP 0015: Steering Council vacancies
====================================

:DEP: 0015
:Author: Sarah Boyce
:Implementation Team: Sarah Boyce
:Shepherd: Carlton Gibson
:Status: Draft
:Type: Process
:Created: 2024-09-21
:Last-Modified: 2024-09-21

.. contents:: Table of Contents
   :depth: 3
   :local:

Abstract
========

This DEP adjusts the Steering Council election process so that the DSF board
must issue candidate registration extensions until sufficient registrations
have been received. It also ensures that the Steering Council must fill
vacant positions within a 3 month time period.

Specification
=============

The process for electing the Steering Council (formerly Technical Board), as
specified in `DEP 10`__, will be adjusted as follows:

* The DSF board MUST extend the registration period for Steering Council
  candidates if they have received less than 5 eligible candidate registrations
  when the registration period closes.

* The DSF board SHALL decide the length of the extension, and MUST continue to
  issue such extensions until they have received sufficient candidate
  registrations.

* The DSF board MAY publish the number of eligible candidate registrations they
  have received at any point during the registration period.

* In the case the current Steering Council has an open vacancy, the Steering
  Council SHALL fill a temporary or permanent vacancy as per the process as
  defined in DEP 10.

* The Steering Council MUST fill vacant positions within a 3 month period. If a
  vacancy has been held open for over 3 months, an election is triggered for a
  new Steering Council.

__ https://github.com/django/deps/blob/main/final/0010-new-governance.rst

Rationale
=========

The last Steering Council election had four candidates for five seats.

The current process for electing a Steering Council does not make allowances
for extensions to be made when insufficient candidate registrations have been
received.

The Steering Council still functions with four members by design. However, this
was to add flexibility and resilience in case a Steering Council member resigns
or is removed.

This ensures the Steering Council must be elected with all vacancies filled. It
also ensures that a Steering Council must replenish itself in the case it is
reduced to four members.

Backwards Compatibility
=======================

N/A

Reference Implementation
========================

As the current Steering Council has four members, upon approval of this DEP,
the 3 month period will begin to fill the vacant position.

Copyright
=========

This document has been placed in the public domain per the Creative Commons
CC0 1.0 Universal license (http://creativecommons.org/publicdomain/zero/1.0/deed).
