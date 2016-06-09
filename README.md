# hello-world
gradle hello world project

1. gradle creates and releases tag
2. cirecleCI sets up git account/credentials
2. cirecleCI auto runs gradle buid with tag releas

## Usage
- change `git_tag` in `build.gradle`
- export VERSION_NUM=v0.0.1
- export IS_OFFICIAL_RELEASE=true
- run `gradle releaseTag -Pversion_num=$VERSION_NUM -Pis_official_release=$IS_OFFICIAL_RELEASE`
