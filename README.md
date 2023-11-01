# starter-reusable-workflows
Panel of reusable workflows for CICD usages with GitHub action

![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

### Workflows Starter

#### Build a Java application with maven

Use this workflow to build a java application package with maven tools. This workflow run a simple package of your application.
The worklow wait a parameter : java_version. Here below an example of the usage of this workflow.

```yaml
jobs:
  build-java-application:
    uses: mattkds/starter-reusable-workflows/.github/workflows/starter-java-maven-build.yml@main
    with:
      java_version: 17
```
