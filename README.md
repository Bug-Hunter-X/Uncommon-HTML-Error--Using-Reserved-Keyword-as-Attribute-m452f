# Uncommon HTML Error: Reserved Keyword as Attribute

This repository demonstrates an uncommon error in HTML: using a reserved keyword as a custom attribute name.  While browsers might not always throw an error, using reserved keywords incorrectly can lead to unexpected behavior or interfere with JavaScript functionality.

The `bug.html` file showcases the error. The `solution.html` file demonstrates the corrected code.

## Bug Description

The problem lies in using the reserved keyword `for` (used for associating labels with form elements) as a custom attribute.  This can cause unpredictable outcomes and may make it difficult to interact with the element using JavaScript.

## Solution

The solution is simply to replace the reserved keyword with a descriptive custom attribute name that doesn't conflict with existing HTML standards.
