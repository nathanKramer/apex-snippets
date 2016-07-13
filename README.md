# Apex Snippets

This is a comprehensive collection of Sublime Text snippets for developing Apex.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Installation](#installation)
- [Getting Started](#getting-started)
  - [Documenting Code](#documenting-code)
  - [Methods](#methods)
  - [Assertions and Debug](#assertions-and-debug)
  - [Visualforce](#visualforce)
  - [Queries and DML](#queries-and-dml)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Installation

Clone this repository in your sublime packages directory.

To navigate there:

`Sublime Text` -> `Preferences` -> `Browser Packages`

## Getting Started

In order to make best use of these snippets, I would recommend reading them.

Here are a few good ones to start with.

### Documenting Code

When documenting a file, use [/*f](/filecomment.sublime-snippet)

When documenting a method, use [/*](/comment.sublime-snippet)

When documenting a test method, use [/*t](/test_method.sublime-snippet)

### Methods

You can create apex methods with [method](/method.sublime-snippet)

For void methods, use the very similar [methodv](/method.sublime-snippet)

For test methods, use [test](/test_method.sublime-snippet)

For test factory methods, use [trm](/test_record_method.sublime-snippet)

### Assertions and Debug

Use [assert](/assert.sublime-snippet) for plain assertions

Use [asserte](/assert_equals.sublime-snippet) for equality assertions

Use [debug](/debug.sublime-snippet) for debugging

### Visualforce

When adding Page messages in your controller (Error, Info, Fatal, Warning):

- [Ame](/add_message_error.sublime-snippet)
- [Ami](/add_message_info.sublime-snippet)
- [Amf](/add_message_fatal.sublime-snippet)
- [Amw](/add_message_warning.sublime-snippet)

To construct a standard controller, use [Aps](/initialise_standard_controller.sublime-snippet)

To construct a standard set controller, use [Apss](/initialise_standard_set_controller.sublime-snippet)

### Queries and DML

For a quick inline query use [query](/soql_query.sublime-snippet)

For a larger query use [querybig](/soql_query_big.sublime-snippet)

For a try catched insert with rollback, try [tcd](/safe_dml.sublime-snippet)
