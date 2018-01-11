# Freshbarks - Tailwind Demo

This is just a quick demo of [Tailwind](https://github.com/tailwindcss/tailwindcss) where I rebuilt one of the FreshBooks pages as my process of actually learning how to use Tailwind.  This is of course not an exact copy, but it's pretty close.  I didn't bother changing the colors to match exactly and some of the spacing isn't exact either.  I also didn't build the table at the bottom of the page.  I did, however, make some improvements to the mobile view, so that'll look a little different from the real, live page.

![mobile view](http://link.joey.io/Q3QpnN/8OssPqCoUd+)
![normal view](http://link.joey.io/nHmh6l/lU47sRrfZG+)

## Things to note

I did make a few tweaks to the `tailwind.js` config file to add a few extra widths and things, but other than that, it's a pretty standard config.  Sorry I didn't commit the initial config so that you could see a diff of my changes, I was being lazy.  :)

## Steps to run

1. `git clone git@github.com:joeybeninghove/freshbarks-tailwind-demo.git`
2. `bundle install`
3. `yarn install`
4. `bundle exec rails db:migrate`
5. `bundle exec webpack`
6. `bundle exec rails server`

Then just visit [http://localhost:3000](http://localhost:3000) to view the page.
