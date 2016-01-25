# Change Log
All notable changes to this project will be documented in this file, with the format recommended at http://keepachangelog.com/.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

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
