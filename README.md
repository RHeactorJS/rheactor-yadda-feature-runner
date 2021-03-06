# yadda-feature-runner

[![npm version](https://img.shields.io/npm/v/@rheactorjs/yadda-feature-runner.svg)](https://www.npmjs.com/package/@rheactorjs/yadda-feature-runner)
[![Build Status](https://travis-ci.org/RHeactorJS/yadda-feature-runner.svg?branch=master)](https://travis-ci.org/RHeactorJS/yadda-feature-runner)
[![Greenkeeper badge](https://badges.greenkeeper.io/RHeactorJS/yadda-feature-runner.svg)](https://greenkeeper.io/) 
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)
[![semantic-release](https://img.shields.io/badge/semver-semantic%20release-e10079.svg)](https://github.com/semantic-release/semantic-release)
[![Code Climate](https://codeclimate.com/github/RHeactorJS/yadda-feature-runner/badges/gpa.svg)](https://codeclimate.com/github/RHeactorJS/yadda-feature-runner)

A feature runner for [yadda](https://github.com/acuminous/yadda)

## Annotations

The following annotations are implemented:

 - `@after`: marks a feature to be run *after* another feature. Features are sorted to ensure that they run in the proper order. 
 - `@pending`: marks a feature or scenario as skipped
 - `@thisonly`: tells the runner to only run this feature. All depending features are run before. 
