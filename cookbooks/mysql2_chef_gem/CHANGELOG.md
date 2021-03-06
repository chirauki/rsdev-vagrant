# mysql2_chef_gem CHANGELOG

## 1.1.0 (2016-04-27)

- Added a chefignore file
- Loosen the dependency on mysql cookbook to allow for the use of the latest version
- Added source_url and issue_url metadata
- Added long_description metadata
- Removed the AWS based Test Kitchen testing and replaced with with kitchen-docker in Travis
- Updated Chefspec format to remove deprecation warnings
- Added Oracle Linux to the metadata

## 1.0.2 (2015-06-29)

- Updating metadata to depend on mysql ~> 6.0

## 1.0.1 (2014-12-25)

- Moving from recipe_eval in to include_recipe LWRP

## 1.0.0 (2014-12-23)

- Replacing recipes with resources
- Mysql and MariaDB providers for linking mysql2 gem
- Expanded platform test coverage

## 0.1.1 (2014-09-15)

- Correct a typo in documentation
- Correct a test failing with Travis CI

## 0.1.0 (2014-09-15)

- Correct documentation
- Correct rubocop offenses

## 0.0.3 (2014-09-12)

- Initial release (copy of mysql-chef_gem, but for mysql2)
