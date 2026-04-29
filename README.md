# CryptoQuant (cryptoquant)

CryptoQuant is a blockchain data analytics platform providing real-time and historical on-chain, exchange flow, miner, derivatives, and stablecoin metrics for Bitcoin, Ethereum, and other major cryptocurrencies. The CryptoQuant API delivers time-series data used by traders, funds, and researchers to gauge market sentiment and capital flows.

**APIs.yml URL:** https://raw.githubusercontent.com/api-evangelist/cryptoquant/refs/heads/main/apis.yml

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party
- **x-type:** company

## Tags

Blockchain, Cryptocurrency, On-Chain Analytics, Market Data, Derivatives

## APIs

### CryptoQuant API

The CryptoQuant API exposes on-chain, exchange flow, market, miner, and stablecoin metrics for major cryptocurrencies via a versioned REST interface.

- Base URL: https://api.cryptoquant.com/v1
- Documentation: https://cryptoquant.com/docs
- Authentication: API key as bearer token
- OpenAPI: [openapi/cryptoquant-openapi.yml](openapi/cryptoquant-openapi.yml)

## Features

- Exchange flow metrics (inflow, outflow, reserve) per exchange
- Miner flow metrics for Bitcoin mining pools
- Network indicators (SOPR, MVRV, NVT)
- Market and derivatives data (OHLCV, open interest)
- Stablecoin reserve and supply metrics
- Multiple time-series resolutions (min, hour, day, block)
- API key authentication via bearer token

## Use Cases

- Trading signals for quantitative crypto strategies
- Risk management and exchange-reserve monitoring
- Miner behavior research and supply forecasting
- Macro crypto research and reporting
- Compliance and market surveillance

## Artifacts

- OpenAPI: [openapi/cryptoquant-openapi.yml](openapi/cryptoquant-openapi.yml)
- JSON Schema: [json-schema/cryptoquant-timeseries-schema.json](json-schema/cryptoquant-timeseries-schema.json)
- JSON-LD Context: [json-ld/cryptoquant-context.jsonld](json-ld/cryptoquant-context.jsonld)
- Vocabulary: [vocabulary/cryptoquant-vocabulary.yml](vocabulary/cryptoquant-vocabulary.yml)
- Spectral Rules: [rules/cryptoquant-rules.yml](rules/cryptoquant-rules.yml)
- Naftiko Capabilities: [capabilities/](capabilities/)

## Maintainers

- Kin Lane (kin@apievangelist.com)
