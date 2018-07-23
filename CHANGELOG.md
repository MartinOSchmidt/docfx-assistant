# Change Log

## v0.1.5

* Recursively create metadata cache directory if required (tintoy/docfx-assistant#10).

## v0.1.3

* Complete move of DocFX project engine to `docfx-project` module on NPM.

## v0.1.2

* Fix cache-refresh bug.

## v0.1.1

* Add document link provider for UIDs in inline (`@xxx`) and XRef (`<xref:xxx>`) styles.

## v0.1.0

* Improve extension startup time.

## v0.0.9

* Persist topic metadata cache in workspace-specific file.

## v0.0.8

* Use chokidar instead of VSCode API for watching DocFX content files (VSCode API is unreliable).

## v0.0.7

* Implement completion provider for topic UIDs.
* Replace UID quick-pick list with completion provider.

## v0.0.6

* Automatically track changes to topic content files in the current workspace.

## v0.0.5

* Support filtering topics by type.

## v0.0.4

* Automatically scan project files on extension startup (unless configured not to).

## v0.0.3

* Add progress reporting when scanning files.

## v0.0.2

* Add link to [license](LICENSE).

## v0.0.1

* Initial release
