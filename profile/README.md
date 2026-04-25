<p align="center">
  <img src="https://raw.githubusercontent.com/TableProApp/TablePro/main/.github/assets/logo.png" width="128" height="128" alt="TablePro">
</p>

<h1 align="center">TablePro</h1>

<p align="center">
  Native database client for Mac and iPhone. MySQL, PostgreSQL, SQLite, MongoDB, Redis, and 15+ more.<br>
  Free and open-source.
</p>

<p align="center">
  <a href="https://github.com/TableProApp/TablePro/releases/latest"><img src="https://img.shields.io/github/v/release/TableProApp/TablePro?style=flat-square&color=blue" alt="Latest Release"></a>
  <a href="https://github.com/TableProApp/TablePro/blob/main/LICENSE"><img src="https://img.shields.io/github/license/TableProApp/TablePro?style=flat-square" alt="License"></a>
  <a href="https://github.com/TableProApp/TablePro/stargazers"><img src="https://img.shields.io/github/stars/TableProApp/TablePro?style=flat-square" alt="Stars"></a>
</p>

<p align="center">
  <a href="https://tablepro.app">Website</a> · <a href="https://docs.tablepro.app">Documentation</a> · <a href="https://github.com/TableProApp/TablePro/releases/latest">Download</a>
</p>

---

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TableProApp/TablePro/main/.github/assets/app-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/TableProApp/TablePro/main/.github/assets/app-light.png">
    <img alt="TablePro macOS database client with SQL editor and data grid" src="https://raw.githubusercontent.com/TableProApp/TablePro/main/.github/assets/app-light.png" width="800">
  </picture>
</p>

## About

TablePro is a native macOS database client built with SwiftUI and AppKit. No Electron, no web views, no Java runtimes. It connects to 18+ databases through a plugin system, with a SQL editor powered by tree-sitter and an AI assistant that helps write and optimize queries.

## Databases

**Built-in**: MySQL, MariaDB, PostgreSQL, Redshift, SQLite, ClickHouse, SQL Server, Redis

**Plugins**: MongoDB, Oracle, DuckDB, Cassandra, Etcd, Cloudflare D1, DynamoDB, BigQuery, libSQL/Turso

## Install

```bash
brew install --cask tablepro
```

Or download from [tablepro.app/download](https://tablepro.app/download). Requires macOS 14.0+, Apple Silicon or Intel.
