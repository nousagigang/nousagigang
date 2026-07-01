# Changelog

All notable changes to this repository will be documented in this file.

## [v1.0.0](https://github.com/nousagigang/nousagigang/releases/tag/v1.0.0) - 2026-07-01

This is the first major release of the website following the initial [`v0.1.0`](https://github.com/nousagigang/nousagigang/releases/tag/v0.1.0) release. It introduces a complete migration to the new infrastructure, a redesigned content system, improved deployment pipeline, author profiles, analytics, and numerous content and usability improvements.

### Highlights

* Successfully migrated the website to the new repository and Hugo-based architecture.
* Added automated deployment to Firebase Hosting using GitHub Actions.
* Introduced author profiles and author pages.
* Expanded the News section with support for richer content and related articles.
* Added site analytics and improved article metadata.
* Improved project documentation and contributor resources.

### Added

* Author system with dedicated author profiles and biographies.
* Author information displayed on articles.
* News article support with featured images and related updates.
* Community progress report.
* Analytics integration.
* Firebase Hosting configuration.
* Status TypeIt animation.
* Member profile pages.
* Additional contributor and community documentation:

  * CONTRIBUTING guide
  * CHANGELOG
  * Legal pages
  * Privacy Policy
  * Terms of Use
  * Resources
* Community roster, history, and contact page improvements.

### Improved

* Updated Hugo configuration and module dependencies.
* Refined site navigation and menus.
* Improved article metadata and taxonomy support.
* Enabled article views and likes.
* Added author display at the bottom of articles.
* Improved member descriptions and profile information.
* Enhanced homepage and landing page content.
* Improved internal links and image handling.
* Updated project documentation.

### Infrastructure

* Implemented automated Firebase deployments via GitHub Actions.
* Migrated from `FirebaseExtended/action-hosting-deploy` to the Firebase CLI.
* Added workflows to automate repository migration and content imports.
* Added workflows for temporary News section enable/disable during deployments.
* Reorganized repository structure for maintainability.

### Content

* Published the 'Rebuilding Day One' news article.
* Added Progress Reports.
* Expanded member biographies and profile information.
* Updated About, Contact, History, and Roster pages.
* Added descriptions for multiple community members.

### Fixed

* Fixed image path handling for news articles.
* Fixed related article generation.
* Resolved asset organization issues.
* Cleaned up duplicate and obsolete media files.
* Removed legacy layouts and deprecated assets.
* Fixed deployment configuration and build issues.

### Maintenance

* Removed obsolete migration workflows after repository migration.
* Cleaned up unused assets and static files.
* Reorganized content directories.
* Updated configuration files across the project.
* Performed various repository cleanup and refactoring tasks.

### Notes

Thanks to everyone who contributed to the migration and development of the project. This release establishes the foundation for future updates and community content.

<p align="center"> ───  ◆  ◆  ◆  ─── </p>

## [0.1.0](https://github.com/nousagigang/nousagigang/releases/tag/v0.1.0) - 2026-06-23

### Added

* Hugo Modules support.
* Blowfish theme integration.
* GitHub Actions deployment workflow.
* Firebase Hosting deployment.

### Notes

This repository is a continuation of the **NSG website project**.

Historical changes prior to [v0.1.0](https://github.com/nousagigang/nousagigang/releases/tag/v0.1.0) are available in the legacy repository:
https://github.com/k4lm3d/nsg/blob/main/CHANGELOG.md
