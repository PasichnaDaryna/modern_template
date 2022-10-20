# SCSS Template

Styles are written in SCSS and compiled into CSS
for the final distribution. The source SCSS files
can be found under `src/` folder and the
distribution-ready files in `stylesheets/`.

## General Info

`stylesheets/main.css` is the main stylesheet file
that we distribute to our clients. That's why it is
important that you compile your changes into that
file before committing.

We use a modified 7-1 pattern for our SCSS files which
fits better with out clients. More on this architecture
can be found in the appendix.

## Dev

If you want to add code to this project, after cloning
the repo, run `yarn install`.

The entry point of the project is `src/main.scss`, which
gets compiled into `stylesheets/main.css`.

To compile one time, run `yarn compile` or to run a watcher
`yarn compile:watch`. There is also a linting script `yarn lint`
if you want to make your code prettier.

## Read

- [SASS Architecture](https://sass-guidelin.es/#architecture)
- [The 7-1 Pattern](https://sass-guidelin.es/#the-7-1-pattern)
- [SASS Basics](https://sass-lang.com/guide)
