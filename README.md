# capability-wifi-info

Atomic authority package for `wifi/info`.

- imports: `#{:wifi-info}`
- effects: `#{:personal-data :network-read}`
- default policy: `:approval-required`
- provider status: `contract-only`

Importing this package does not grant runtime authority. Tamaki must
request it explicitly and Kototama must admit the sealed envelope.

```sh
clojure -M:test
```
