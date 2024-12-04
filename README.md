# Hack Bug: Missing Return Type Annotation
This repository demonstrates a common error in Hack programming: a missing return type annotation in a function declaration.
The `main` function is missing a return type annotation, which causes a compilation error. The provided solution adds the missing annotation to fix the issue.

## Bug Description
The `main` function lacks a return type annotation. In Hack, functions must explicitly declare their return type. Omitting this annotation results in a compiler error.

## Solution
The solution adds a `void` return type annotation to the `main` function, explicitly stating that it doesn't return any value.