# MUDpatch Test Repository

## Introduction

This is a test repository for the MUDpatch patch management tool.

## Test Branches

This repo has several branches, some which merge cleanly and some which will not.

- ISSUE1-0.1 is based off the `0.1` tag from `main` and implements the `test_method_2` function.
- ISSUE2-0.1 is based off the `0.1` tag from `main` and adds a second python file.
- Issue3-0.1 is based off the `0.1` tag from `main` and adds another method to `test-file-1.py`, however as it is based on the `0.1` tag (where `test_method_2` is unimplemented, if you merge this branch after the `ISSUE1-0.1` branch then you will get a merge conflict.
