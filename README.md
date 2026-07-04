# QuantInfra

**QuantInfra** is an open algorithmic trading platform for building, testing, deploying, and operating systematic trading strategies.

The platform provides a unified programming model across the entire strategy lifecycle:

- High-performance event-driven backtesting
- Production-ready live trading
- Unified broker and exchange connectivity
- Extensible architecture for custom strategies, indicators, analytics, optimization pipelines, and infrastructure

QuantInfra is designed for individual quantitative traders, proprietary trading firms, hedge funds, and fintech companies who want institutional-grade infrastructure without building everything from scratch.

## Documentation

Documentation, tutorials, and examples are available at:

https://quantinfra.gitbook.io/quantinfra-docs

## Repositories

### QuantInfra SDK
**License:** Apache 2.0

The SDK contains the public API used to develop trading strategies, indicators, and integrations. It is intended to remain stable and can be freely used in both open-source and commercial projects. The QuantInfra SDK is licensed under the Apache 2.0 license. You can use it to develop proprietary trading strategies and commercial applications without any obligation to publish your source code. Strategies built using the SDK remain your intellectual property.

Repository: https://github.com/QuantInfra/quantinfra-sdk

---

### QuantInfra Standard Indicators
**License:** Apache 2.0

A collection of commonly used technical indicators implemented on top of the QuantInfra SDK.
The indicators are licensed under the Apache 2.0 license. You can use them to develop proprietary trading strategies and commercial applications without any obligation to publish your source code. Strategies built using the SDK remain your intellectual property.

Repository: https://github.com/QuantInfra/quantinfra-standard-indicators

---

### QuantInfra Core
**License:** Business Source License (BSL)

The core platform contains the trading engine, backtesting framework, live execution infrastructure, data management, and platform services.

The BSL allows source code access and modification while protecting the commercial platform from being redistributed as a competing product. Commercial use for operating trading strategies in test and production environments is permitted under the terms of the license.

Repository: https://github.com/quantinfrasolutions/quantinfra-core
