# Summary

- [Introduction](./introduction.md)

- [Quick Start](./quick-start.md)

- [Common tasks](./tasks.md)
  - [Mutating Policies](./mutating-policies.md)

- [Architecture](./architecture.md)

- [Writing Policies](./writing-policies/index.md)
  - [Policy Specification](./writing-policies/spec/01-intro.md)
    - [Settings](./writing-policies/spec/02-settings.md)
    - [Validating policies](./writing-policies/spec/03-validating-policies.md)
    - [Mutating policies](./writing-policies/spec/04-mutating-policies.md)
    - [Context aware policies](./writing-policies/spec/05-context-aware-policies.md)
  - [Rust](./writing-policies/rust/01-intro.md)
    - [Create a new policy](./writing-policies/rust/02-create-policy.md)
    - [Define policy settings](./writing-policies/rust/03-define-policy-settings.md)
    - [Write the validation logic](./writing-policies/rust/04-write-validation-logic.md)
    - [Write a mutation policy](./writing-policies/rust/05-mutation-policy.md)
    - [Logging](./writing-policies/rust/06-logging.md)
    - [Build and distribute](./writing-policies/rust/07-build-and-distribute.md)
  - [Rego](./writing-policies/rego/01-intro.md)
    - [Open Policy Agent](./writing-policies/rego/open-policy-agent/01-intro.md)
      - [Create a new policy](./writing-policies/rego/open-policy-agent/02-create-policy.md)
      - [Build and run](./writing-policies/rego/open-policy-agent/03-build-and-run.md)
      - [Distribute](./writing-policies/rego/open-policy-agent/04-distribute.md)
    - [Gatekeeper](./writing-policies/rego/gatekeeper/01-intro.md)
      - [Create a new policy](./writing-policies/rego/gatekeeper/02-create-policy.md)
      - [Build and run](./writing-policies/rego/gatekeeper/03-build-and-run.md)
      - [Distribute](./writing-policies/rego/gatekeeper/04-distribute.md)
    - [Builtin support](./writing-policies/rego/02-builtin-support.md)
  - [Go](./writing-policies/go/01-intro.md)
    - [Create a new policy](./writing-policies/go/02-scaffold.md)
    - [Define policy settings](./writing-policies/go/03-policy-settings.md)
    - [Write the validation logic](./writing-policies/go/04-validation.md)
    - [End-to-end testing](./writing-policies/go/05-e2e-tests.md)
    - [Logging](./writing-policies/go/06-logging.md)
    - [GitHub Action integration](./writing-policies/go/07-automate.md)
    - [Distribute policy](./writing-policies/go/08-distribute.md)
  - [Swift](./writing-policies/swift.md)
  - [TypeScript](./writing-policies/typescript.md)
  # Enable these sections once we update them to waPC
  #- [Domain Specific Language](./writing-policies/dsl.md)
  #- [Other languages](./writing-policies/other-languages.md)
  
- [Distributing Policies](./distributing-policies.md)
  - [Custom Certificate Authorities](./distributing-policies/custom-certificate-authorities.md)
  - [OCI Registries support](./distributing-policies/oci-registries-support.md)
  
- [Testing Policies](./testing-policies/01-intro.md)
  - [While creating a policy](./testing-policies/02-policy-authors.md)
  - [Before deployment](./testing-policies/03-cluster-operators.md)
  
- [Operator Manual](./operator-manual/01-intro.md)
  - [Configuring PolicyServers](./operator-manual/policy-servers/01-custom-cas.md)
  - [Telemetry](./operator-manual/telemetry/01-quickstart.md)
    - [OpenTelemetry](./operator-manual/telemetry/opentelemetry/01-quickstart.md)
    - [Metrics](./operator-manual/telemetry/metrics/01-quickstart.md)
      - [Reference](./operator-manual/telemetry/metrics/02-reference.md)
    - [Tracing](./operator-manual/telemetry/tracing/01-quickstart.md)
