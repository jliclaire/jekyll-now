---
layout: post
title: Use Bootstrap in Ruby on Rails
---
### Install Bootstrap Gem
The gem to use is [Bootstrap Ruby Gem](https://github.com/twbs/bootstrap-rubygem#b-other-ruby-frameworks).
The step is as below
1. open 'Gemfile', add - `gem 'bootstrap', '~> 4.3.1'` under `development`
2. run `bundle install`
3. in file 'application.css' add code line `@import "bootstrap";` at the bottom
4. change the file name to 'application.scss'
5. add `jquery-rails` to the 'Gemfile' under `development`
6. run `bundle install`
7. add below code to `application.js` file
   - `//= require jquery3`
   - `//= require popper`
   - `//= require bootstrap`

### Example of using Bootstrap
```
  <%= link_to 'View Blogs', controller: 'posts', class: "btn btn-primary" %>
```
