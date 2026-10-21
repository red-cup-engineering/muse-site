# muse-assist public information site

<!-- 561-group-standards:badges:start -->
[![Red Cup Engineering](https://img.shields.io/badge/561%20Group-Red%20Cup%20Engineering-c0392b)](https://github.com/red-cup-engineering)
[![License: MIT](https://img.shields.io/badge/license-MIT-c0392b)](LICENSE)
[![Indigenous data: CARE](https://img.shields.io/badge/Indigenous%20data-CARE-4b6f44)](https://github.com/red-cup-engineering/.github/blob/main/GOVERNANCE.md)
[![Tips welcome](https://img.shields.io/badge/tips-welcome-d4a017)](https://github.com/561-group/.github/blob/main/TIPS.md)
<!-- 561-group-standards:badges:end -->

This static information site describes the 561 Group `muse-assist` early-alpha project. It is not an assistant interface, a supported product package, or evidence of a deployed service. Meta Muse is a separate product. The project license remains undecided and no release is represented here.

## Source and generation

The public pages and VICTOR project configuration are generated from the content records and configuration data in `2026-09-27-muse-assist-site-content-fabrication.md`. The accepted generator inputs, when available, are the derived Markdown records under `content/` and `static-site-publisher.config.mjs`. Generated HTML and other publisher artifacts are outputs; do not edit them by hand. Do not add private repository records, credentials, assay material, or unlisted assets to the public build.

Use a shared VICTOR revision accepted under the canonical authored-home fabrication order. Content and configuration admission, rendered-page observations, and promotion evidence are retained outside the public output tree; the presence of generated files alone does not establish acceptance.

## Stage and check a candidate

From this site directory, install the declared tool with `pnpm install --frozen-lockfile --ignore-scripts`, matching the normal Code registry receiving policy. The exact pinned publisher is received from the registry; no monorepo-relative source checkout or global command is required. After the authored-home predecessor is accepted and the work order is admitted, build into a new empty directory outside the serving tree:

    pnpm exec static-site-publisher build content /tmp/muse-assist-site-candidate --config=static-site-publisher.config.mjs

Run the publisher's configured double-build check:

    pnpm exec static-site-publisher check content --config=static-site-publisher.config.mjs

For a local draft preview, bind only to loopback:

    pnpm exec static-site-publisher serve content --host=127.0.0.1 --port=8561 --config=static-site-publisher.config.mjs

These commands are documented publisher interfaces, not evidence they have run for this candidate. A candidate remains unaccepted until the exact staged bytes pass manifest/refusal checks and independent reading, claim, accessibility, route, and no-script checks required by the site LLD. A local preview is not deployment.

## Release state

The earlier hand-authored public files are migration material; the generated reading destinations replace them only after acceptance. A local build does not establish deployment or a released package. Licensing is pending a customer decision.
