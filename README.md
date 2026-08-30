# Cline Gateway

A high-availability Cline API gateway written in Rust.

> Work in progress. The project is being developed incrementally.

## Goals

- OpenAI-compatible API gateway
- Anthropic Messages API compatibility
- Multiple Cline API keys
- Sticky key routing and failover
- Rate-limit and cooldown tracking
- Web administration interface
- Usage and token metrics
- Single-binary deployment

## Development

```bash
cargo fmt --all -- --check
cargo check --all-targets --all-features --locked
cargo clippy --all-targets --all-features --locked -- -D warnings
cargo test --all-targets --all-features --locked
```

## License

This project is licensed under the MIT License.
