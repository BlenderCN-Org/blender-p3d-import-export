# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)

## [Unreleased]
### Added
### Changed
### Fixed

## [1.3.0] - 2019-01-27
### Added
- Meshes can now be autocentered to behave like makep3d would
- Added timestamps to the export-log.txt

## [1.2.1] - 2018-11-14
### Fixed
- Probably fixed position export.

## [1.2.0] - 2018-11-14
### Added
- export-log.txt file will be created on evry export in the same folder as the export path. This logs contains info about export process and includes list of all meshes ready for carinfo.cca
### Fixed
- Collision and Trace flags are now correctly set on export, so CD should not crash when trying to load LOD's or other stuff.

## [1.1.1] - 2018-11-13
### Fixed
- Material names can now have any length.
- UV autogenerated for the end model if none are present in blender.