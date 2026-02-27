<div align="center">

<img src="https://ghrb.waren.build/banner?header=subscription-cleanse%20%F0%9F%92%B8&subheader=Find%20forgotten%20subscriptions%20bleeding%20your%20bank%20account&bg=0a1628&secondaryBg=1e3a5f&color=e8f0fe&subheaderColor=7eb8da&headerFont=Inter&subheaderFont=Inter&support=false" alt="subscription-cleanse" width="100%">

<br><br>

**Find forgotten subscriptions bleeding your bank account.**

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) plugin from the [not-my-job](https://github.com/drewburchfield/not-my-job) marketplace.

![License](https://img.shields.io/badge/license-MIT-blue)

</div>

<br>

## What it does

Audits your subscriptions by combining bank CSV analysis with email reconnaissance. Parses transactions from multiple banks, decodes obfuscated charges, cross-references with your inbox, and outputs an interactive HTML report.

## Features

- Bank CSV parsing: Apple Card, Chase, Mint, Capital One, and more
- Transaction decoding: Privacy.com, PayPal, Square, Google, Apple
- Email recon via Gmail MCP integration
- Interactive HTML audit report

## Requirements

- Bank CSV export (any supported format)
- Gmail MCP server (for email reconnaissance)

## Install

```
claude plugins install subscription-cleanse@not-my-job
```

## License

MIT
