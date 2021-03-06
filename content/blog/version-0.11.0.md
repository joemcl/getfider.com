+++
date = "2018-03-25"
title = "Fider 0.11 released with option to edit and delete ideas"
categories = ["releases"]
description = "In this month’s release of Fider, we’ve been working mostly on internal changes, but managed to add option edit and delete ideas"
author = "goenning"
+++

### Introduction

It's very well known that as the size of the codebase grows, so does the complexity and time needed to maintain it. This is a common characteristic of most software programs and thus, not different for Fider.

As we evolve one version a month we need to always look back and improve older code, even those small pieces that are still working sometimes needs some love. Refactoring older code to make it easier to read, maintain and change is something we'll be doing more often moving forward. We want Fider to be a place where anyone with any skill level can join, change, extend and improve it.

Starting today on all new release blog posts, we'll list some (or even all) other activities that have been done, which usually relates to refactoring, tooling changes, bug fixes and enhancements.

### #1: Delete Ideas

<figure style="float:right;margin-left:20px;">
  <img src="/images/blog/delete-idea-button.png" />
</figure>

Administrators are now able to delete ideas that are not yet closed yet. This is specifically useful to remove spam / off-topic ideas. Although it can be used to remove duplicate ideas, we recommend the usage of `Duplicate` status as transfers vote to the original idea.

<div style="clear:both;" />

### #2: Edit Comments

Comment authors can now edit their own comments to fix typos or include any missing information. Administrators are also able to edit all comments on their site. Once a comment has been edited, a small comment is show beside the original comment date.

<figure>
  <img src="/images/blog/edit-comments.png" />
</figure>

### Other Changes on Fider 0.11

- enhancement: tie up all tables with tenant_id ([#279](https://github.com/getfider/fider/issues/279)) 
- refactoring: removed jQuery ([#171](https://github.com/getfider/fider/issues/171))
- refactoring: react naming convention and folder structure ([#276](https://github.com/getfider/fider/issues/276))
- refactoring: internal changes that requires less SQL queries to run ([#281](https://github.com/getfider/fider/issues/281), [#277](https://github.com/getfider/fider/issues/277), [#280](https://github.com/getfider/fider/issues/280))
- tooling: add Prettier ([#309](https://github.com/getfider/fider/issues/309)) thanks to [@LukeSheard](https://github.com/LukeSheard)
- tooling: update JS & Go dependencies ([#273](https://github.com/getfider/fider/issues/273))
- fix: goroutine Leak ([#286](https://github.com/getfider/fider/issues/286))
- fix: race condition on worker process ([#313](https://github.com/getfider/fider/issues/313))
- docs: Review Fider contributing process, files, templates ([#278](https://github.com/getfider/fider/issues/278))

### What's next?

Help us shape the future of Fider. Visit our [feedback forum](https://feedback.fider.io/) and raise your voice. Tell us what to do next.