---
layout: post
title: Why you should be using Jekyll
date: 2022-01-19 11:00:00
categories: [Jekyll, Ruby]
---

## Summary

Jekyll is a really nifty tool made with Ruby that can seriously expedite some of your daily work. Using predefined Jekyll themes and a couple lines of markdown, you can create a visually pleasing website that serves static content, just like this one!

## Jekyll Setup

Setting up Jekyll is usually a breeze depending on the environment. In order to install Jekyll, you will need to setup Ruby and any compilation tools necessary to get started with Ruby Gems. This entire process can be handled through the installer provided on [Ruby's website](https://www.ruby-lang.org/en/). You'll find that the first project you complete with Ruby will succeed with very little effort, but in the future you'll run into issues with dependency resolutions between different versions of Ruby Gems. This is why users opt for different methods of environment management, such as [Ruby Version Manager](https://rvm.io/) or a variety of Docker containers that already contain the gems you will need. For those of you experienced with Docker, I would highly recommend using the [container with Jekyll and Ruby preinstalled](https://github.com/envygeeks/jekyll-docker). This will allow you to jump straight into development without any dependency conflicts, as well as providing a very easy deployment method in the future.

## Developing With Jekyll

The primary appeal of Jekyll is the ability to make appealing web pages just by writing in basic markdown. Creating new pages on your website is as easy as creating a new markdown file, and declaring what the layout of the generated web page should be.

Jekyll is also the perfect tool for setting up websites using Github Pages. Github Pages offers completely free hosting and is built to be used with Jekyll. All you have to do is properly configure the repository, and updates can be easily made to your Jekyll website through simple git commits.