# CSS ::before Pseudo-element Content Cutoff Issue

This repository demonstrates a peculiar issue related to the CSS `::before` pseudo-element where its content gets unexpectedly cut off when using `white-space: nowrap;` and the content exceeds the container's width.

## Problem Description

The problem lies in the unexpected truncation of text within a `::before` pseudo-element when the text length surpasses the container's width, and `white-space: nowrap;` is applied.  This can lead to visual inconsistencies and unexpected layout behavior. 

## Solution

The provided solution illustrates how to solve this problem using `text-overflow: ellipsis;` or wrapping the text. Refer to `bugSolution.css` for the corrected code.