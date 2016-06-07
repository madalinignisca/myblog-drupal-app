# Modern Drupal Application Skeleton

## Intro
I made this repo as I wasn't happy with issues I was encountering
using other solutions and I wanted to use Drupal in the modern
style of web applications.

This repo is very light, is intended for only small network transfers
and automating deployments, using Composer, Drush and Drupal Console.

For me it was critical to work 100% well with [Open DevShop](http://getdevshop.com/).

If you are not used to modern web apps, then this is a good
starting point to dig in.

Drupal is installed in the __web__ folder, being pooled by Composer
and placed there.

As you may know, Drupal 8+ uses the concept of PHP packages,
most notable some important Symfony packages, some Zend Framework
packages and as it evolves you are going to see more and more added
to your project.

In this skeleton, Composer is instructed to place the __Vendor__
folder in the root of the project, outside of the Drupal root.
