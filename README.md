# Developer Conventions
Conventions for development and workflows across web application development technologies.

## Website
[Interactive Pioneers Developer conventions](http://conventions.interactive-pioneers.com)

## Adding a new category
- Categories are automatically added when added to a post

## Adding a new topic
- Posts live in `_posts`
- A new post must be name `year-month-day-name.md`
- All posts require yaml front-matter e.g.
```
---
layout: default
title: Javascript
category: Coding conventions
---
```
## Sorting categories
- Categories occur in the order of the posts first using it, because a specific order is not required right now

## Development setup
- `gem install jekyll`
- `bundle install`
- `jekyll serve --baseurl""`
- open http://0.0.0.0:4000

## Styling
- All convention specific styles are in `_conventions.scss`.
- All other styles should be kept in sync with the main website
