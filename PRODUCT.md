# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML/CSS on GitHub Pages (custom domain `portfolio.ovalente.online`, `.nojekyll`, no build step). Existing codebase; no framework.

## Users

- Primary: people who arrive from an app's App Store page, a GitHub repo, a TestFlight link, or a social post and want to know who made it and what else Joao has built. They are curious, on a phone or Mac, and decide in seconds whether to tap into an app.
- Secondary (inferred from the "independent Apple developer" positioning; unconfirmed): other Apple-platform developers and indie-app watchers evaluating the work, and potential collaborators or clients.

## Product Purpose

A personal portfolio for Joao Valente, an independent Apple developer. It exists to present the shipped apps and open-source projects in one place, make each one reachable in one tap, and give a short, honest picture of the person behind them. Success: a visitor lands on an app they care about and opens it (App Store, TestFlight, website, or source) without friction, and leaves with a clear sense of a real, consistent body of native work.

## Positioning

An independent developer who ships native Swift/SwiftUI apps across iPhone, iPad and Mac, most of them built around local or private AI (summaries, grounded Q&A, on-device models) and calmer ways to read and research, with source code public for nearly everything. The mix of shipped App Store products plus a deep open-source bench of Mac utilities (trackpad gestures, menu-bar tools, ScreenCaptureKit) is the truthful differentiator.

## Operating Context

- Content lives in a single `index.html` with `style.css`; assets (app icons, portrait, self-hosted fonts) live in `assets/`.
- Deployed by pushing to `main` on `Joaov41/Joaov41.github.io`.
- The developer is frequently updating copy and adding projects, so structure must make adding a card/row trivial.

## Capabilities and Constraints

Shipped apps (facts and links from current site):
- RedSum, iPhone/iPad/Mac, App Store id6757315148, website redapp.digital, source github.com/Joaov41/redapp
- RSSum, iPhone/iPad/Mac, App Store id6743862589, website rssapp.top, source github.com/Joaov41/Rss
- Vortex, iPhone/iPad, TestFlight KTsJ3qz4, website vortex.engineer, source github.com/Joaov41/Vortex-Browser
- Aiassistant, macOS, open source, website ai.assistant.community, source github.com/Joaov41/Aiassistant

Open-source projects: LocalTypist, Grid Switcher, Focus Latch, FloatDeck, RedbarApp, HideMyData (fork of mkbula/HideMyData), Redactor, AppleGPT (iOS/iPadOS and macOS repos, modified fork), ScreencapNative. Descriptions and platform tags in `index.html` are confirmed product truth and must be preserved verbatim unless the user edits them.

Constraints:
- No JavaScript frameworks; plain static HTML/CSS is fine. Small JS for progressive enhancement is acceptable.
- Must work without JS.
- Self-hosted fonts only (no third-party font CDN).
- No invented claims: no download counts, ratings, testimonials, press, or client names.

## Brand Commitments

- Name: Joao Valente. Title line: "Independent Apple Developer".
- Voice (from existing copy): direct, plain, understated; "useful", "private", "calmer", "focused". No hype.
- Visual identity: none pinned. The user asked for a full redesign and delegated the direction ("you suggest"). The current look (Geist, orange/acid accents, italic serif emphasis, mono eyebrows) is evidence of the subject only, not authority.

## Evidence on Hand

- App icons: `assets/redsum.jpg`, `assets/rssum.jpg`, `assets/vortex.png`, `assets/aiassistant.png`
- Portrait: `assets/joao-valente.jpg`
- Fonts currently bundled: `assets/geist-latin.woff2`, `assets/geist-mono-latin.woff2` (may be replaced)
- No app screenshots, no device mockups, no testimonials, no metrics. Future work must not fabricate these; if screenshots are wanted, the user provides them.

## Product Principles

1. The work leads. Apps and projects are the content; the portfolio is the frame.
2. One tap to the real thing. Every app and project has its primary destination visible and obvious.
3. Truth over polish. Only real facts, real assets, real links.
4. Native sensibility. The site should feel made by someone who builds careful Mac/iOS software.
5. Easy to maintain. Adding an app or project is a copy-paste of one block.

## Accessibility & Inclusion

- WCAG AA contrast for all text, including on colored surfaces.
- Functional text never below 11px; body text at 16px or above.
- Honor `prefers-reduced-motion` and `prefers-color-scheme`.
- Fully usable with keyboard; visible focus states.
