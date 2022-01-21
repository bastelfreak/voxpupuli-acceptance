# Changelog

All notable changes to this project will be documented in this file.

## [1.1.0](https://github.com/voxpupuli/voxpupuli-acceptance/tree/1.1.0) (2022-01-21)

[Full Changelog](https://github.com/voxpupuli/voxpupuli-acceptance/compare/1.0.1...1.1.0)

**Implemented enhancements:**

- cleanup dependencies; depend on beaker \>= 4.33.0 [\#35](https://github.com/voxpupuli/voxpupuli-acceptance/pull/35) ([bastelfreak](https://github.com/bastelfreak))

**Fixed bugs:**

- Add puppetlabs\_spec\_helper 4 compatibility [\#34](https://github.com/voxpupuli/voxpupuli-acceptance/pull/34) ([bastelfreak](https://github.com/bastelfreak))

**Merged pull requests:**

- cleanup release CI job; publish to github packages [\#36](https://github.com/voxpupuli/voxpupuli-acceptance/pull/36) ([bastelfreak](https://github.com/bastelfreak))
- Document vagrant beaker backend [\#33](https://github.com/voxpupuli/voxpupuli-acceptance/pull/33) ([bastelfreak](https://github.com/bastelfreak))
- Add Ruby 3.1 to CI matrix [\#32](https://github.com/voxpupuli/voxpupuli-acceptance/pull/32) ([bastelfreak](https://github.com/bastelfreak))

## [1.0.1](https://github.com/voxpupuli/voxpupuli-acceptance/tree/1.0.1) (2021-07-03)

[Full Changelog](https://github.com/voxpupuli/voxpupuli-acceptance/compare/1.0.0...1.0.1)

**Fixed bugs:**

- Fix applying spec/setup\_acceptance\_node.erb [\#27](https://github.com/voxpupuli/voxpupuli-acceptance/pull/27) ([smortex](https://github.com/smortex))

## [1.0.0](https://github.com/voxpupuli/voxpupuli-acceptance/tree/1.0.0) (2021-05-21)

[Full Changelog](https://github.com/voxpupuli/voxpupuli-acceptance/compare/0.3.0...1.0.0)

**Implemented enhancements:**

- Change fact handling into a setting [\#25](https://github.com/voxpupuli/voxpupuli-acceptance/pull/25) ([ekohl](https://github.com/ekohl))
- Add a rake task [\#22](https://github.com/voxpupuli/voxpupuli-acceptance/pull/22) ([ekohl](https://github.com/ekohl))
- Support a Puppet-based acceptance node setup script [\#21](https://github.com/voxpupuli/voxpupuli-acceptance/pull/21) ([ekohl](https://github.com/ekohl))
- Add shared examples [\#20](https://github.com/voxpupuli/voxpupuli-acceptance/pull/20) ([ekohl](https://github.com/ekohl))
- Add integration with beaker-hiera [\#19](https://github.com/voxpupuli/voxpupuli-acceptance/pull/19) ([ekohl](https://github.com/ekohl))

**Fixed bugs:**

- Correct namespace of Fixtures + add an example [\#24](https://github.com/voxpupuli/voxpupuli-acceptance/pull/24) ([ekohl](https://github.com/ekohl))

**Merged pull requests:**

- Add a test suite [\#23](https://github.com/voxpupuli/voxpupuli-acceptance/pull/23) ([ekohl](https://github.com/ekohl))
- Use released github\_changelog\_generator [\#18](https://github.com/voxpupuli/voxpupuli-acceptance/pull/18) ([ekohl](https://github.com/ekohl))
- Expand the documentation with hypervisors and links [\#17](https://github.com/voxpupuli/voxpupuli-acceptance/pull/17) ([ekohl](https://github.com/ekohl))
- Convert to Github Actions [\#15](https://github.com/voxpupuli/voxpupuli-acceptance/pull/15) ([ekohl](https://github.com/ekohl))

## [0.3.0](https://github.com/voxpupuli/voxpupuli-acceptance/tree/0.3.0) (2020-10-09)

[Full Changelog](https://github.com/voxpupuli/voxpupuli-acceptance/compare/0.2.1...0.3.0)

**Implemented enhancements:**

- Add support to store environment variables as facts [\#13](https://github.com/voxpupuli/voxpupuli-acceptance/pull/13) ([ekohl](https://github.com/ekohl))

## [0.2.1](https://github.com/voxpupuli/voxpupuli-acceptance/tree/0.2.1) (2020-05-20)

[Full Changelog](https://github.com/voxpupuli/voxpupuli-acceptance/compare/0.2.0...0.2.1)

**Merged pull requests:**

- Avoid broken beaker versions 4.22.0 and 4.23.0 [\#11](https://github.com/voxpupuli/voxpupuli-acceptance/pull/11) ([dhoppe](https://github.com/dhoppe))
- Fix typo in README.md / Add Badges to README.md [\#10](https://github.com/voxpupuli/voxpupuli-acceptance/pull/10) ([bastelfreak](https://github.com/bastelfreak))

## [0.2.0](https://github.com/voxpupuli/voxpupuli-acceptance/tree/0.2.0) (2020-04-29)

[Full Changelog](https://github.com/voxpupuli/voxpupuli-acceptance/compare/0.1.1...0.2.0)

**Implemented enhancements:**

- Add fixtures module helper [\#8](https://github.com/voxpupuli/voxpupuli-acceptance/pull/8) ([ekohl](https://github.com/ekohl))

**Merged pull requests:**

- Fix typo in README.md [\#6](https://github.com/voxpupuli/voxpupuli-acceptance/pull/6) ([wbclark](https://github.com/wbclark))

## [0.1.1](https://github.com/voxpupuli/voxpupuli-acceptance/tree/0.1.1) (2020-04-06)

[Full Changelog](https://github.com/voxpupuli/voxpupuli-acceptance/compare/0.1.0...0.1.1)

**Merged pull requests:**

- Add a default rake task [\#4](https://github.com/voxpupuli/voxpupuli-acceptance/pull/4) ([ekohl](https://github.com/ekohl))

## [0.1.0](https://github.com/voxpupuli/voxpupuli-acceptance/tree/0.1.0) (2020-04-06)

[Full Changelog](https://github.com/voxpupuli/voxpupuli-acceptance/compare/0ac3f59d43beced663c9dbf6ff9999f9549358d0...0.1.0)

**Merged pull requests:**

- add travis secret [\#2](https://github.com/voxpupuli/voxpupuli-acceptance/pull/2) ([bastelfreak](https://github.com/bastelfreak))
- Initial version [\#1](https://github.com/voxpupuli/voxpupuli-acceptance/pull/1) ([ekohl](https://github.com/ekohl))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
