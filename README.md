## Apoxy Custom OTEL Collector

There isn't much special about this custom OTEL collector, it is simply a minimal collector with:

- ClickHouse Exporter
- Debug Exporter
- ZPages Extension
- OTLP Receiver
- Batch Processor
- Memory Limiter

This collector was assembled using the [opentelemetry-collector builder](https://github.com/open-telemetry/opentelemetry-collector/tree/main/cmd/builder).
