# Tooling

## About

Supporting tooling.

## cfgBuilder

Reads a sitemap index and generates a config file for Gleaner
with each sitemap in the index a source entry.

A basic attempt is made to parse the URL into a logic name with
an index number appended to ensure uniqueness.  This is a rather
brittle approach though given the potential changes in the sitemap
URL.  So, you may need to alter those elements of the code to
address your particular needs.

[cfgBuilder](./README.md)
