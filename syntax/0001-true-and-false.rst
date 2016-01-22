**************
true and false
**************

===============  =============================================
Proposal #:      0001
Type:            Standards Track
Affects-DRM:     Yes
Author:          Bruce Mitchener, Jr.
Status:          Draft
===============  =============================================

.. contents:: Contents
   :local:


Abstract
========

Dylan currently uses ``#t`` and ``#f`` to represent true and false
boolean values. This note proposes using ``true`` and ``false``.


Rationale
=========

While using ``#t`` and ``#f`` fits in with the Dylan tradition of using
``#`` to indicate a special sort of syntax (like ``#(...)`` or ``#[...]``
or ``#"..."``), this syntax is not as familiar for people who are used
to other programming languages.

Even C has picked up ``true`` and ``false`` constants with the advent of
the ``stdbool.h`` header in C99.


Specification
=============

(Write here how the actual specification would have to be updated.)

Reference Implementation
========================

This proposal has not yet been implemented.
