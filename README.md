# F# Mutable Variable Bug

This repository demonstrates a common error in F# involving mutable variables and unexpected behavior within functions.  The issue arises from how mutable variables are passed and modified within the function scope.

## The Problem

The provided code attempts to swap the values of two mutable variables. However, the outcome is not the intended swap. This unexpected behavior is due to how F# handles mutable variables and their references.

## Solution

The solution demonstrates how to correctly swap the mutable variables to achieve the intended result. This involves a deeper understanding of F#'s handling of mutability and references within functions.
