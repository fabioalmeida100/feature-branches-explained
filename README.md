# Feature branch explained

## What is a feature branch?

A feature branch is a branch that is created from the main branch (usually `master`) to develop a new feature. It is used to develop a new feature without affecting the main branch. Once the feature is complete, it can be merged back into the main branch.

## Why use feature branches?

Feature branches are useful because they allow you to develop a new feature without affecting the main branch. This means that you can work on a new feature without worrying about breaking the main branch. It also means that you can work on multiple features at the same time without worrying about them interfering with each other.

## How to create a feature branch

To create a feature branch, you need to first create a new branch from the main branch. If you are using Git, you can do this by following these steps:

-  Checkout the main branch: `git checkout master` | `git checkout main`
-  Create a new branch from the main branch: `git checkout -b feature-branch`
-  Checkout the new branch: `git checkout feature-branch`

## How to merge a feature branch

Once you have finished working on a feature branch, you can merge for master/main branch through a pull request or directly merge it into the main branch. 

## Feature branch in action

Below is an example of how a feature branch works. In this example you can see a QA branch that is created from the main branch. 

This branch possibilite the QA team to test the new feature without affecting the master/main branch. Once the feature is complete, it can be merged back into the master/main branch.

![Feature branch animated image](images/images/features-branches.gif)

---
By [fabioDeveloper.com](https://www.fabioDeveloper.com) & [CriarProgramas.com](https://www.criarprogramas.com) | 2023


