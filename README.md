## Hi, I'm Josh

Lead full-stack / smart-contract engineer. Runner, coder, pool player.

I ship a lot of small, focused libraries and CLIs. GitHub only lets me pin six of them, so this page is the long version: every public project worth a look, grouped by what it actually is.

[![Website](https://img.shields.io/badge/site-joshuahubbard.dev-0a0a0a?style=flat-square)](https://joshuahubbard.dev)
[![Email](https://img.shields.io/badge/email-josh%40joshuahubbard.dev-0a0a0a?style=flat-square)](mailto:josh@joshuahubbard.dev)
[![GitHub](https://img.shields.io/github/followers/jhubbardsf?style=flat-square&label=followers)](https://github.com/jhubbardsf)

---

### Svelte / SvelteKit

Most of my open source mileage lives here. Combined, these packages do roughly **60k installs a month** on npm.

| Project | Stars | Installs / month | What it does |
| --- | --- | --- | --- |
| [`svelte-inview`](https://github.com/svelte-inview/svelte-inview) | ![stars](https://img.shields.io/github/stars/svelte-inview/svelte-inview?style=flat-square&label=%20) | ![dm](https://img.shields.io/npm/dm/svelte-inview?style=flat-square&label=%20) | Svelte action that fires when an element enters or leaves the viewport. Co-maintainer. |
| [`svelte-sortablejs`](https://github.com/jhubbardsf/svelte-sortablejs) | ![stars](https://img.shields.io/github/stars/jhubbardsf/svelte-sortablejs?style=flat-square&label=%20) | ![dm](https://img.shields.io/npm/dm/@jhubbardsf/svelte-sortablejs?style=flat-square&label=%20) | Svelte wrapper around Sortable.js. Drag-and-drop reorderable lists. |
| [`svelte-speech-recognition`](https://github.com/jhubbardsf/svelte-speech-recognition) | ![stars](https://img.shields.io/github/stars/jhubbardsf/svelte-speech-recognition?style=flat-square&label=%20) | ![dm](https://img.shields.io/npm/dm/svelte-speech-recognition?style=flat-square&label=%20) | Web Speech API as a Svelte store. |
| [`vite-plugin-svelte-console-remover`](https://github.com/jhubbardsf/vite-plugin-svelte-console-remover) | ![stars](https://img.shields.io/github/stars/jhubbardsf/vite-plugin-svelte-console-remover?style=flat-square&label=%20) | ![dm](https://img.shields.io/npm/dm/vite-plugin-svelte-console-remover?style=flat-square&label=%20) | Strip `console.*` calls from Svelte production builds. |
| [`sveltekit-remote-fn-plugin`](https://www.npmjs.com/package/sveltekit-remote-fn-plugin) |  | ![dm](https://img.shields.io/npm/dm/sveltekit-remote-fn-plugin?style=flat-square&label=%20) | Vite plugin for SvelteKit remote functions. |

### AI / MCP servers

Model Context Protocol servers and adjacent tooling for agentic workflows.

| Project | Installs / month | What it does |
| --- | --- | --- |
| [`imperium-mcp`](https://github.com/jhubbardsf/imperium-mcp) | ![dm](https://img.shields.io/npm/dm/imperium-mcp?style=flat-square&label=%20) | MCP server for Imperium (Mercor) docs and guidelines. |
| [`dfns-mcp`](https://github.com/jhubbardsf/dfns-mcp) | ![dm](https://img.shields.io/npm/dm/dfns-mcp?style=flat-square&label=%20) | MCP server giving agents typed access to DFNS API docs and SDK examples. |
| [`humantyping-ts`](https://github.com/jhubbardsf/HumanTypingTS) | ![dm](https://img.shields.io/npm/dm/humantyping-ts?style=flat-square&label=%20) | Realistic human-like typing simulation for TypeScript / Playwright. Variable timing, neighbor-key errors, fatigue, the whole bit. [Demo.](https://jhubbardsf.github.io/HumanTypingTS/) |
| [`ghost-cursor-playwright-mcp`](https://github.com/jhubbardsf/ghost-cursor-playwright-mcp) |  | Playwright MCP server with human-like cursor movement baked in. |
| [`conventional-commit-ai`](https://github.com/jhubbardsf/conventional-commit-ai) |  | CLI that turns staged diffs into Conventional Commits messages. |
| [`claude-plans-organizer`](https://github.com/jhubbardsf/claude-plans-organizer) | ![dm](https://img.shields.io/npm/dm/claude-plans-organizer?style=flat-square&label=%20) | Browse and rename Claude Code plans by human-readable name. |
| [`localstack-mcp-server`](https://github.com/jhubbardsf/localstack-mcp-server) |  | MCP server wrapping LocalStack for AWS-in-a-box agents. |

### Web3 / Smart contracts

| Project | Stars | What it does |
| --- | --- | --- |
| [`diamond-2-hardhat-v6`](https://github.com/jhubbardsf/diamond-2-hardhat-v6) | ![stars](https://img.shields.io/github/stars/jhubbardsf/diamond-2-hardhat-v6?style=flat-square&label=%20) | EIP-2535 Diamond reference, ported to TypeScript + Hardhat + Ethers v6. Public template. |
| [`@jhubbardsf/ethers-decode-error`](https://www.npmjs.com/package/@jhubbardsf/ethers-decode-error) |  | Decode ethers.js contract errors into human-readable messages. |
| [`coinmarketcap-dex-sdk`](https://www.npmjs.com/package/coinmarketcap-dex-sdk) |  | TypeScript SDK for the CoinMarketCap DEX API. |

### Developer tools

Things I built because the official UX bugged me.

| Project | What it does |
| --- | --- |
| [`sopsx`](https://github.com/jhubbardsf/sopsx) | SOPS wrapper that auto-selects the right `AWS_PROFILE` based on the KMS key in the file. Distributed via Homebrew tap. |
| [`aws-sso-refresh`](https://github.com/jhubbardsf/aws-sso-refresh) | macOS daemon that keeps AWS SSO sessions alive in the background. Homebrew tap. |
| [`adzuna-sdk`](https://github.com/jhubbardsf/adzuna-sdk) | Fully type-safe TypeScript SDK for the Adzuna jobs API. Built on Ky, runs on Bun and Node 18+. |
| [`@jhubbardsf/sonner`](https://www.npmjs.com/package/@jhubbardsf/sonner) | Sonner fork with structured logging hooks for debugging toasts in tests. |

---

### Stats

[![Josh's GitHub stats](https://github-readme-stats.vercel.app/api?username=jhubbardsf&show_icons=true&hide_border=true&theme=transparent&include_all_commits=true&count_private=true)](https://github.com/jhubbardsf)
[![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=jhubbardsf&layout=compact&hide_border=true&theme=transparent&langs_count=8)](https://github.com/jhubbardsf)
