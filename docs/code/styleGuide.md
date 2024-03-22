# Style Guide for ColdFusion Code
================================================

- [Introduction](#introduction)
	- [Summary](#summary)
	- [When to Ignore the Rules of this Guide](#when-to-ignore-the-rules-of-this-guide)
	- [Should I Refactor Legacy Code?](#should-i-refactor-legacy-code)



## Introduction:
### Summary
This document provides coding conventions for contributing to ColdFusion code at foobar. This guide is based on the [PEP 8 Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/) in both outline and convention, however there are some key differences. This guide should always be referenced first and takes precedence over any conflicts with PEP 8.

### When to Ignore the Rules of this Guide
The rules of this guide should be adhered to for all new development, stand-alone functions, and stand-alone blocks of code. When working within legacy ColdFusion code, **with the exception of practices that pose security risks, local style supersedes the preferred style.**

### Should I Refactor Legacy Code?
When creating a Pull Request (PR) against legacy code you should NOT do large refactors that are out of scope of the task. While refactoring legacy code to more modern styles is encouraged, this should be done via a separate PR opened for the sole purpose of a refactor.
