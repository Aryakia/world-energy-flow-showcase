# World Energy Flow — Public Showcase

**A Systems View of Global Energy**

| | |
|---|---|
| **Project type** | Energy-market analysis · systems thinking · research publishing |
| **Role** | Creator, analyst, and developer |
| **Status** | Active publication platform |
| **Live platform** | https://worldenergyflow.com |
| **Canonical source** | Private production repository |
| **Public disclosure** | Product architecture, analytical method, public features, and non-sensitive implementation details |

---

## Executive summary

World Energy Flow is an independent bilingual energy-analysis platform that connects market movements to the physical infrastructure, policy choices, geopolitical events, expectations, and feedback loops that produce them.

It is also the permanent digital home of **World of Energy**, a weekly analysis series initiated through Sharif University of Technology's Energy Department in **2023**.

The objective is not simply to report that a benchmark moved. The platform asks **what system structure, constraint, expectation, or policy mechanism helps explain the move**.

## Current platform scope

### Energy-market coverage

Recurring briefs track major oil and natural-gas benchmarks including:

- **Brent crude**
- **WTI crude**
- **Henry Hub natural gas**
- **Dutch TTF natural gas**
- **JKM LNG**

The publication cadence is organized around a recurring **Saturday market brief**.

### Bilingual research publishing

The platform supports:

- English and Farsi content
- right-to-left rendering for Farsi
- persistent language preference
- permanent issue routes
- research/archive continuity with the original World of Energy series

### Historical analytical dashboard

The public platform includes analytical views such as:

- price history
- period returns
- sample volatility
- rolling averages
- event context
- causal-driver interpretation

The dashboard calculates from the observations actually available in the archive; it does not silently synthesize missing historical observations.

### Open publication infrastructure

Public-facing infrastructure includes:

- downloadable CSV data for digital issues and benchmark history
- RSS feed
- XML sitemap
- robots metadata
- publication calendar
- share links
- canonical metadata

## Analytical standard

World Energy Flow deliberately separates five kinds of statements:

1. **Sourced observation** — what a reliable source or market observation reports
2. **Calculated metric** — a transparent transformation of available observations
3. **Analytical inference** — an interpretation of interacting drivers
4. **Forecast / scenario** — a forward-looking conditional statement
5. **Limitation** — missing evidence, uncertainty, or boundary of the analysis

This separation is central to the platform's editorial design.

## Systems-thinking approach

Energy markets are treated as dynamic systems rather than isolated price series. Analysis can connect:

- supply and demand
- storage and inventories
- infrastructure bottlenecks
- production and transport capacity
- policy and sanctions
- geopolitical disruptions
- expectations and market response
- substitution and demand adaptation
- delays and feedback

The goal is to produce a causal narrative that remains anchored to evidence.

## Technology and delivery architecture

The production application uses a modern static web architecture built with:

- Next.js 16
- React 19
- TypeScript
- Tailwind CSS / PostCSS
- static production export
- automated validation through GitHub Actions

A static export keeps the public publication lightweight and avoids unnecessary server-side infrastructure for normal page delivery.

## Brand architecture

- **World Energy Flow** — the broader public research and analysis platform
- **A Systems View of Global Energy** — platform tagline
- **World of Energy** — the established weekly/editorial series preserved within the platform

Historical references to World of Energy remain intact because they identify the original publication series.

## Long-term research direction

The architecture is designed to expand selectively into:

- energy security
- energy-transition policy
- country analysis
- System Dynamics
- policy scenarios
- interactive models
- deeper historical energy datasets

New sections are intended to appear only when there is substantive research content behind them.

## Public/private boundary

This showcase does **not** expose the canonical source repository, credentials, deployment configuration, internal editorial workflow, unpublished analysis, or any non-public data. Public downloadable datasets are treated as intentionally public; everything else remains separated from the showcase unless deliberately released.

## Author

**Arya Kia**  
Energy systems · policy · market analysis · systems thinking
