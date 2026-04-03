# API Stability Rules

- All public APIs in std are part of the language contract.
- Breaking changes require an RFC and a deprecation cycle.
- Every public function must have documentation and at least one test.
- Prefer zero-cost abstractions that compile to optimal native code.
