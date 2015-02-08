# Chaos Cologne

static site for http://chaos.cologne

## Install

### Ruby Version

ruby 2.2 (lower should be fine)

### Instructions

Install required ruby packages with bundler:

    gem install bundler
    bundle install

## Nanoc

[Nanoc](http://nanoc.ws) is a static site generator.

### Compile static pages

    nanoc compile

### Start a webserver to view pages in a browser

    nanoc view

### Watch output directory for changes    

    guard

## Upload to server

    rsync
