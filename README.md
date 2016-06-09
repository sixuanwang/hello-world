# hello-world
gradle hello world project

1. gradle creates and releases tag
2. circleCI sets up git use and SSH permission
3. circleCI sets two env variables VERSION_NUM and IS_OFFICIAL_RELEASE
4. circleCI auto runs gradle build with tag release

## Usage
- change `git_tag` in `build.gradle`
- export VERSION_NUM=v0.0.1
- export IS_OFFICIAL_RELEASE=true
- run `gradle releaseTag -Pversion_num=$VERSION_NUM -Pis_official_release=$IS_OFFICIAL_RELEASE`

## CI
https://circleci.com/gh/sixuanwang/hello-world/34
