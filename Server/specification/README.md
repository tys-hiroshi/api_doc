# generate CHANGELOG.md

```
docker pull ubuntu
```

## make file ~/.bash_profile

export CHANGELOG_GITHUB_TOKEN="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"


## run docker

```
docker run -t -i ubuntu /bin/bash
```

```
cd project/tys-hiroshi
git clone https://github.com/tys-hiroshi/api_doc.git
cd api_doc/Server/specification
github_changelog_generator -u tys-hiroshi -p api_doc
```

### .github_changelog_generator

```
pr-label=### Added
enhancement-label=### Changed
bugs-label=### Fixed
enhancement-labels=enhancement,change
bug_labels=bug,hotfix
exclude-labels=release
unreleased-label=Unreleased
```
