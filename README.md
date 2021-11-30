# Reusable Workflows for Github Actions

This repository holds reusable workflows which could be used to build, test, lint and deploy Node JS apps to AWS ECS

## Usage

### Build

```yaml
uses: upcounsel/workflows/.github/workflows/build-and-test-node-service.yml@main
```

### Lint 

```yaml
uses: upcounsel/workflows/.github/workflows/eslint-node-service.yml@main
```

### Deploy to AWS ECS

```yaml
uses: upcounsel/workflows/.github/workflows/deploy-node-service.yml@main
```


For detailed  information on `inputs` and `secrets` syntax see individual workflow files

