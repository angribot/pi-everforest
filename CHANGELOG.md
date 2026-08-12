# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.3] - 2026-08-12

### Fixed

- Point `homepage` in `package.json` at the pi.dev package page.

## [0.1.2] - 2026-08-12

## [0.1.1] - 2026-08-11

### Fixed

- Missing `repository`/`homepage`/`bugs` metadata in `package.json`.

## [0.1.0] - 2026-08-11

### Added

- Six everforest schemes (`dark`/`light` × `hard`/`medium`/`soft`) as pi themes, each mapping the upstream palette to all pi color tokens (51 required + optional `thinkingMax`).
- pi theme package scaffolding: `package.json` with `pi.themes` manifest for install via `pi install git:...`.
