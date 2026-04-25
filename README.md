# Cloud Native Buildpacks (cloud-native-buildpacks)

Cloud Native Buildpacks (CNB) is a CNCF-graduated specification and set of tooling for transforming application source code into OCI images. The project unifies the Heroku and Cloud Foundry buildpack ecosystems around an open standard for detection, build, and image export.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cloud-native-buildpacks/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** opensource

## Tags

- Buildpacks, CNCF, Containers, Images, OCI, Open Source, Platform, Reproducible Builds

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-23

## APIs

### Buildpack API
The contract between a buildpack and the lifecycle.

**Spec:** [https://github.com/buildpacks/spec/blob/main/buildpack.md](https://github.com/buildpacks/spec/blob/main/buildpack.md)

### Platform API
The contract between the lifecycle and a platform such as pack or kpack.

**Spec:** [https://github.com/buildpacks/spec/blob/main/platform.md](https://github.com/buildpacks/spec/blob/main/platform.md)

### Distribution API
How buildpacks and builders are packaged and distributed as OCI artifacts.

**Spec:** [https://github.com/buildpacks/spec/blob/main/distribution.md](https://github.com/buildpacks/spec/blob/main/distribution.md)

### pack CLI
The reference command-line interface.

**Source:** [https://github.com/buildpacks/pack](https://github.com/buildpacks/pack)

### CNB Lifecycle
Reference implementation of the Buildpack and Platform APIs.

**Source:** [https://github.com/buildpacks/lifecycle](https://github.com/buildpacks/lifecycle)

### kpack
Kubernetes-native CNB implementation.

**Source:** [https://github.com/buildpacks-community/kpack](https://github.com/buildpacks-community/kpack)

### Buildpack Registry
Index of published buildpacks.

**Registry:** [https://registry.buildpacks.io/](https://registry.buildpacks.io/)

## Common Properties

- [Website](https://buildpacks.io/)
- [Documentation](https://buildpacks.io/docs/)
- [Specification](https://github.com/buildpacks/spec)
- [GitHub](https://github.com/buildpacks)
- [CNCF](https://www.cncf.io/projects/buildpacks/)
- [JSON-LD Context](json-ld/cloud-native-buildpacks-context.jsonld)
- [Spectral Ruleset](rules/cloud-native-buildpacks-rules.yml)
- [Naftiko Capabilities](capabilities/cloud-native-buildpacks.yaml)

## Maintainers

**FN:** Kin Lane

**Email:** kinlane@gmail.com
