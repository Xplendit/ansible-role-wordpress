# Change log

This file contains al notable changes to the wordpress Ansible role.

This file adheres to the guidelines of [http://keepachangelog.com/](http://keepachangelog.com/). Versioning follows [Semantic Versioning](http://semver.org/).

## 1.1.1 - 2015-10-07

### Changes

- Fixed missing value of `wordpress_themes`

## 1.1.0 - 2015-10-07

### Added

- Install plugins with role variable `wordpress_plugins`
- Install themes with role variable `wordpress_themes`

## 1.0.0 - 2015-04-28

First release!

### Added

- Installs Wordpress and generates `wp-config.php` with safe secret keys and salts

