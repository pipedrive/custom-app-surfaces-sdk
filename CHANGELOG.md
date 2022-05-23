# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- New event `CLOSE_CUSTOM_MODAL` for listening the updates from custom surface modal

### Updated
- Rename `Modal` type `EMBEDDED_ACTION` to `JSON_MODAL`
- Rename `Modal` type `CUSTOM_SURFACE` to `CUSTOM_MODAL`

## [0.3.0] - 2022-05-19

### Added
- New type `CUSTOM_SURFACE` for `OPEN_MODAL` command

## [0.2.0] - 2022-05-06

### Added
- New `CLOSE_MODAL` command

## [0.1.1] - 2022-05-05

### Updated
- Rename FOCUS tracking event

## [0.1.0] - 2022-03-25

- Detect page focus and blur
- Add initialization command and method
- Add new command - get signed token
- Add new command - open modal. Supported modals are: deal, organization, person and embedded action.
- Add new command - resize surface
- Add new command - show confirmation modal
- Add new command - show snackbar
- Add event listener functionality
- Add option to listen for panel collapse and expand event
- Add surface unique id detection and pass it to postMessage invocations

