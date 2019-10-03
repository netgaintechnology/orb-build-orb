# build-orb

[![CircleCI](https://circleci.com/gh/netgaintechnology/orb-build-orb.svg?style=svg)](https://circleci.com/gh/netgaintechnology/orb-build-orb) [![CircleCI Community](https://img.shields.io/badge/community-CircleCI%20Discuss-343434.svg)](https://discuss.circleci.com/c/ecosystem/orbs)

An orb managing the build phase jobs.

## Usage

For full usage guidelines, see the [orb registry listing](http://circleci.com/orbs/registry/orb/netgaintechnology/orb-build-orb).

### Example

Following is an example of a build pipeline.

```yaml
version: 2.1

orbs:
  build-orb: netgaintechnology/build-orb@x.y.z
workflows:
  version: 2
  builds:
    jobs:
      - build-orb/golang_build
```

## Contributing

We welcome [issues](https://github.com/netgaintechnology/orb-build-orb/issues) to and [pull requests](https://github.com/netgaintechnology/orb-build-orb/pulls) against this repository!
