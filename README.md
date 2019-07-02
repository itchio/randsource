# randsource

[![Build Status](https://travis-ci.org/itchio/randsource.svg?branch=master)](https://travis-ci.org/itchio/randsource)
[![GoDoc](https://godoc.org/github.com/itchio/randsource?status.svg)](https://godoc.org/github.com/itchio/randsource)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/itchio/randsource/blob/master/LICENSE)
[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

randsource is a small Go library that provides an io.Reader that returns random data

**It is developed for internal use, I don't intend to take pull requests.**

It contains:

  * `ewma`: an exponential weighted moving average
  * `united`: formatting routines for bytes
  * `state`: a set of callbacks for log messages & progresses
  * `probar`: a CLI progress bar
  * `counter`: counting wrappers for `io.Reader` and `io.Writer`
  * `tracker`: a speed/ETA estimator for task progress

