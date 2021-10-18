# Change Log
All notable changes to this project will be documented in this file, with the format recommended at http://keepachangelog.com/.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

## 0.3.3 / 2021-10-18

* Re-organize ligatures
* Properly identify weights for style variants
* Change font names to match OTF guidelines

## 0.3.2 / 2021-09-26

* Re-add substitutions
* Add |> ligature

## 0.3.1 / 2021-06-19

* Use standard postscript em width
* normalize font height between variants

## 0.3.0 / 2021-06-15

* Add italic and bold font variants

## 0.2.0 / 2016-01-27

* Use underscores and dots in glyph names in a more conventional way. [#9]

## 0.1.2 / 2016-01-25

* Add a small nick to `==` ligature to distinguish from single `=`.

## 0.1.1 / 2016-01-25

* Don't use `=>` ligature in `<=>` ("spaceship" comparator operator).

## 0.1.0 / 2016-01-22

* Clean up metadata.

## 0.0.3 / 2016-01-22

* Add `<-` ligature (not `<=`, since that's usually not an arrow).

## 0.0.2 / 2016-01-22

* Widen `->` ligature to match width of `=>.` [#2]

## 0.0.1 / 2016-01-22

* Add equality ligatures (`==`, `===`, `!=`, `/=`, `!==`).
* Make all characters monospace by using `calt` for ligatures as in Monoid. [#1]
* Add `->` and `=>` ligatures.
