# Changelog

## 1.3.1 - 2023-08-20

### paperless-ngx ansible role 1.3.1

#### Bug Fixes

- fix(deps): add pkg-config @GamerBene19 ([#98](https://github.com/paperless-ngx/ansible/pull/98))
- fix: https://github.com/ansible/molecule/issues/4017 @stevenengland ([#99](https://github.com/paperless-ngx/ansible/pull/99))

**Full Changelog**: https://github.com/paperless-ngx/ansible/compare/1.3.0...1.3.1

## 1.3.0 - 2023-08-11

### paperless-ngx ansible role 1.3.0

#### Features

- feat: add support for v1.16 and 1.17 @stevenengland ([#90](https://github.com/paperless-ngx/ansible/pull/90))
- feat: add support for debian 12 @stevenengland ([#89](https://github.com/paperless-ngx/ansible/pull/89))

#### Bug Fixes

- fix(deps): bump requests from 2.28.1 to 2.31.0 in /.github/workflows @dependabot ([#92](https://github.com/paperless-ngx/ansible/pull/92))
- fix(deps): bump pip from 23.1.2 to 23.2.1 in /.github/workflows @dependabot ([#88](https://github.com/paperless-ngx/ansible/pull/88))
- fix(deps): bump yamllint from 1.31.0 to 1.32.0 in /.github/workflows @dependabot ([#76](https://github.com/paperless-ngx/ansible/pull/76))
- fix(deps): bump danielchabr/pr-labels-checker from 3.1 to 3.3 @dependabot ([#73](https://github.com/paperless-ngx/ansible/pull/73))
- fix(deps): bump pip from 23.1 to 23.1.2 in /.github/workflows @dependabot ([#69](https://github.com/paperless-ngx/ansible/pull/69))
- fix(deps): bump yamllint from 1.30.0 to 1.31.0 in /.github/workflows @dependabot ([#64](https://github.com/paperless-ngx/ansible/pull/64))
- fix(deps): bump ansible from 7.4.0 to 7.5.0 in /.github/workflows @dependabot ([#70](https://github.com/paperless-ngx/ansible/pull/70))

#### Maintenance

- build: remove requests dependency @stevenengland ([#93](https://github.com/paperless-ngx/ansible/pull/93))
- style(ansible lint): make compliant with newest version @stevenengland ([#91](https://github.com/paperless-ngx/ansible/pull/91))
- test(molecule): change molecule version to use >5.0.0 @stevenengland ([#80](https://github.com/paperless-ngx/ansible/pull/80))

#### Dependencies

<details>
<summary>7 changes</summary>
- fix(deps): bump requests from 2.28.1 to 2.31.0 in /.github/workflows @dependabot ([#92](https://github.com/paperless-ngx/ansible/pull/92))
- fix(deps): bump pip from 23.1.2 to 23.2.1 in /.github/workflows @dependabot ([#88](https://github.com/paperless-ngx/ansible/pull/88))
- fix(deps): bump yamllint from 1.31.0 to 1.32.0 in /.github/workflows @dependabot ([#76](https://github.com/paperless-ngx/ansible/pull/76))
- fix(deps): bump danielchabr/pr-labels-checker from 3.1 to 3.3 @dependabot ([#73](https://github.com/paperless-ngx/ansible/pull/73))
- fix(deps): bump pip from 23.1 to 23.1.2 in /.github/workflows @dependabot ([#69](https://github.com/paperless-ngx/ansible/pull/69))
- fix(deps): bump yamllint from 1.30.0 to 1.31.0 in /.github/workflows @dependabot ([#64](https://github.com/paperless-ngx/ansible/pull/64))
- fix(deps): bump ansible from 7.4.0 to 7.5.0 in /.github/workflows @dependabot ([#70](https://github.com/paperless-ngx/ansible/pull/70))
</details>
**Full Changelog**: https://github.com/paperless-ngx/ansible/compare/1.2.0...1.3.0
## 1.2.0 - 2023-04-26

### paperless-ngx ansible role 1.2.0

#### Features

- feat: add 1.14 support @stevenengland ([#66](https://github.com/paperless-ngx/ansible/pull/66))

#### Bug Fixes

- fix(deps): bump ansible-lint from 6.14.3 to 6.15.0 in /.github/workflows @dependabot ([#62](https://github.com/paperless-ngx/ansible/pull/62))
- fix(deps): bump pip from 23.0.1 to 23.1 in /.github/workflows @dependabot ([#59](https://github.com/paperless-ngx/ansible/pull/59))
- fix(deps): bump peter-evans/create-pull-request from 4 to 5 @dependabot ([#57](https://github.com/paperless-ngx/ansible/pull/57))
- fix(deps): bump ansible-lint from 6.14.2 to 6.14.3 in /.github/workflows @dependabot ([#50](https://github.com/paperless-ngx/ansible/pull/50))
- fix(deps): bump ansible from 7.3.0 to 7.4.0 in /.github/workflows @dependabot ([#52](https://github.com/paperless-ngx/ansible/pull/52))

#### Maintenance

- test: remove unsused tests coming from role init @stevenengland ([#63](https://github.com/paperless-ngx/ansible/pull/63))

#### Dependencies

<details>
<summary>5 changes</summary>
- fix(deps): bump ansible-lint from 6.14.3 to 6.15.0 in /.github/workflows @dependabot ([#62](https://github.com/paperless-ngx/ansible/pull/62))
- fix(deps): bump pip from 23.0.1 to 23.1 in /.github/workflows @dependabot ([#59](https://github.com/paperless-ngx/ansible/pull/59))
- fix(deps): bump peter-evans/create-pull-request from 4 to 5 @dependabot ([#57](https://github.com/paperless-ngx/ansible/pull/57))
- fix(deps): bump ansible-lint from 6.14.2 to 6.14.3 in /.github/workflows @dependabot ([#50](https://github.com/paperless-ngx/ansible/pull/50))
- fix(deps): bump ansible from 7.3.0 to 7.4.0 in /.github/workflows @dependabot ([#52](https://github.com/paperless-ngx/ansible/pull/52))
</details>
**Full Changelog**: https://github.com/paperless-ngx/ansible/compare/1.1.1...1.2.0
## 1.1.1 - 2023-04-01
### paperless-ngx ansible role 1.1.1

#### Maintenance

- refactor: rewrite checks for ansible hosts ansible version @stevenengland ([#53](https://github.com/paperless-ngx/ansible/pull/53))

**Full Changelog**: https://github.com/paperless-ngx/ansible/compare/1.1.0...1.1.1

## 1.1.0 - 2023-03-25

### paperless-ngx ansible role 1.1.0

#### Features

- feat(vars): add PAPERLESS_PRE_CONSUME_SCRIPT @stevenengland ([#46](https://github.com/paperless-ngx/ansible/pull/46))

#### Bug Fixes

- fix(deps): bump yamllint from 1.29.0 to 1.30.0 in /.github/workflows @dependabot ([#45](https://github.com/paperless-ngx/ansible/pull/45))

#### Documentation

- docs(readme): add paragraphs for backup, postgresql, updates @stevenengland ([#47](https://github.com/paperless-ngx/ansible/pull/47))

#### Maintenance

- refactor(backup): remove incomplete backup feature @stevenengland ([#42](https://github.com/paperless-ngx/ansible/pull/42))

#### Dependencies

- fix(deps): bump yamllint from 1.29.0 to 1.30.0 in /.github/workflows @dependabot ([#45](https://github.com/paperless-ngx/ansible/pull/45))

**Full Changelog**: https://github.com/paperless-ngx/ansible/compare/1.0.2...1.1.0

## 1.0.2 - 2023-03-09

### paperless-ngx ansible role 1.0.2

#### Bug Fixes

- fix(NLTK): download NLTK data if NLTK is enabled @stevenengland ([#39](https://github.com/paperless-ngx/ansible/pull/39))
- fix: Bump ansible from 7.2.0 to 7.3.0 in /.github/workflows @dependabot ([#30](https://github.com/paperless-ngx/ansible/pull/30))
- fix: Bump ansible-lint from 6.13.1 to 6.14.1 in /.github/workflows @dependabot ([#36](https://github.com/paperless-ngx/ansible/pull/36))
- fix: Bump falti/dotenv-action from 1.0.2 to 1.0.4 @dependabot ([#28](https://github.com/paperless-ngx/ansible/pull/28))

#### Documentation

- docs(contrib): update document for better reading flow @stevenengland ([#38](https://github.com/paperless-ngx/ansible/pull/38))

#### Maintenance

- test: reorganize tests in seperate files @stevenengland ([#40](https://github.com/paperless-ngx/ansible/pull/40))
- ci(dependabot): add commit message pattern to support conv. commit @stevenengland ([#37](https://github.com/paperless-ngx/ansible/pull/37))
- test: add distro as dimension to GH actions matrix @stevenengland ([#35](https://github.com/paperless-ngx/ansible/pull/35))

#### Dependencies

- fix: Bump ansible from 7.2.0 to 7.3.0 in /.github/workflows @dependabot ([#30](https://github.com/paperless-ngx/ansible/pull/30))
- fix: Bump ansible-lint from 6.13.1 to 6.14.1 in /.github/workflows @dependabot ([#36](https://github.com/paperless-ngx/ansible/pull/36))
- fix: Bump falti/dotenv-action from 1.0.2 to 1.0.4 @dependabot ([#28](https://github.com/paperless-ngx/ansible/pull/28))

**Full Changelog**: https://github.com/paperless-ngx/ansible/compare/1.0.1...1.0.2

## 1.0.1 - 2023-03-07

### paperless-ngx ansible role 1.0.1

#### Bug Fixes

- fix(service units): change mode to world accessible (644) @stevenengland ([#31](https://github.com/paperless-ngx/ansible/pull/31))

#### Maintenance

- test(molecule): consolidate Dockerfiles @stevenengland ([#32](https://github.com/paperless-ngx/ansible/pull/32))

**Full Changelog**: https://github.com/paperless-ngx/ansible/compare/...1.0.1
