# Lab 06

In this lab, you have to add authentication using (devise)[https://github.com/heartcombo/devise] and authorization using (cancancan)[https://github.com/CanCanCommunity/cancancan].

Be sure to use the app that you have been using in the previous labs.

## Instructions

1. Create the `User` model using devise.

2. Create the association between your existing models and the new `User` model.

## Requirements

At least you must comply with:

1. `User`s must me logged in to be able to create a `post` or add a `comment`. But it is not necessary in order to read a `post` and view all posts available.

2. A `user` must be able to edit and delete their own `posts` and `comments`, not another `user`s.

## Important

You must use Bootstrap to style your application.

