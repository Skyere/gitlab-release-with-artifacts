# About
That is project to build some file like jar, exe, msixbundle or something else from source code using gitlab CI/CD
And after that will create release with source files and artifacts which would create using your script
# How to use
- Type your version of release in VERSION file
- Type your build script in .source/build.yml
- Add your repo info in .gitlab/ci/auto-release.yml to add attach your artifacts in release
- Configure gitlab CI/CD
