-------------------------------------------------------------------------

@rmz01 ➜ /workspaces/nextra-example (main) $ pnpm i
Lockfile is up to date, resolution step is skipped
Packages: +264
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

   ╭──────────────────────────────────────────────────────────────────╮
   │                                                                  │
   │                Update available! 9.11.0 → 9.12.3.                │
   │   Changelog: https://github.com/pnpm/pnpm/releases/tag/v9.12.3   │
   │                Run "pnpm add -g pnpm" to update.                 │
   │                                                                  │
   │         Follow @pnpmjs for updates: https://x.com/pnpmjs         │
   │                                                                  │
   ╰──────────────────────────────────────────────────────────────────╯

Downloading next@13.0.6: 8.56 MB/8.56 MB, done
Downloading @next/swc-linux-x64-gnu@13.0.6: 26.09 MB/26.09 MB, done
Downloading @next/swc-linux-x64-musl@13.0.6: 25.94 MB/25.94 MB, done
Downloading typescript@4.9.3: 11.62 MB/11.62 MB, done
Progress: resolved 264, reused 0, downloaded 264, added 264, done
node_modules/.pnpm/@napi-rs+simple-git-linux-x64-gnu@0.1.8/node_modules/@napi-rs/simple-git-linux-x64-gnu: Running postinstall script, done in 71ms
node_modules/.pnpm/@napi-rs+simple-git-linux-x64-musl@0.1.8/node_modules/@napi-rs/simple-git-linux-x64-musl: Running postinstall script, failed in 84ms (skipped as optional)

dependencies:
+ next 13.0.6
+ nextra 2.2.14
+ nextra-theme-docs 2.2.14
+ react 18.2.0
+ react-dom 18.2.0

devDependencies:
+ @types/node 18.11.10
+ typescript 4.9.3

Done in 7.2s
-------------------------------------------------------------------------

@rmz01 ➜ /workspaces/nextra-example (main) $ pnpm dev

> nextra-docs-template@0.0.1 dev /workspaces/nextra-example
> next dev

ready - started server on 0.0.0.0:3000, url: http://localhost:3000
info  - automatically enabled Fast Refresh for 3 custom loaders
warn  - Found lockfile missing swc dependencies, patching...
warn  - Lockfile was successfully patched, please run "npm install" to ensure @next/swc dependencies are downloaded
event - compiled client and server successfully in 2.2s (151 modules)
Attention: Next.js now collects completely anonymous telemetry regarding usage.
This information is used to shape Next.js' roadmap and prioritize features.
You can learn more, including how to opt-out if you'd not like to participate in this anonymous program, by visiting the following URL:
https://nextjs.org/telemetry
