# Unexpected NaN with undefined values in JavaScript function

This repository demonstrates a common JavaScript issue where undefined values lead to NaN results, even with explicit null checks.

## Problem Description
The `foo` function aims to add two numbers. It correctly handles `null` values.  However, using `undefined` results in `NaN`. This is because `undefined` + number evaluates to NaN in JavaScript.

## Solution
The improved version explicitly checks for both `null` and `undefined` values and handles them appropriately.