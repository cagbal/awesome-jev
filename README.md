# awesome-jev [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A list of Jev-related projects and resources for reference.

## Disclaimer

None of the projects listed here are approved or endorsed by me (cagbal). This repository is only a reference list; inclusion does not mean that a project has been audited, certified, or verified as safe, reliable, or suitable for any purpose.

Evaluate each project independently and use it at your own risk. This list is provided as-is, without warranties. To the fullest extent permitted by applicable law, the maintainer and contributors disclaim liability for loss or damage arising from reliance on this list or use of any linked project.

## What is Jev?

Jev is TypeSafe AI’s model for turning unstructured input into fast, typed decisions with probabilities that software can act on directly.

Learn more in TypeSafe AI’s [introduction to System One models and Jev](https://typesafe.ai/blog/introducing-system-one-models-and-jev).

## Official projects

- [typesafe-sdk-python](https://github.com/typesafe-ai/typesafe-sdk-python) connects Python applications to TypeSafe’s structured decision API.
- [typesafe-sdk-js](https://github.com/typesafe-ai/typesafe-sdk-js) provides JavaScript and TypeScript clients with answer types inferred from the questions.
- [system-one-adapter-python](https://github.com/typesafe-ai/system-one-adapter-python) lets developers compare conventional LLMs with TypeSafe through a compatible decision interface.
- [skills](https://github.com/typesafe-ai/skills) teaches coding agents how to build workflows using TypeSafe’s typed judgments.

## Community projects

- [jev-mcp](https://github.com/jkudish/jev-mcp) exposes Jev through MCP tools for evidence checking, content screening, and candidate ranking.
- [jev-review](https://github.com/devagrawal09/jev-review) uses Jev to assess code changes or entire codebases and display findings in a local dashboard.
- [blink](https://github.com/ellipsis-dev/blink) finds files matching natural-language requests through multiple Jev-guided searches of a directory tree.
- [typesafe-cli](https://github.com/y0usaf/typesafe-cli) brings Jev’s probability, choice, and scoring queries to the terminal.
- [typesafe-mario](https://github.com/fhshaik/typesafe-mario) lets Jev choose Super Mario Bros. controller actions from structured emulator telemetry.
- [jev-belay](https://github.com/valentynkit/jev-belay) reads the Claude Code transcript for evidence and asks Jev four questions before letting an unverified "done" through, failing open on any error.
- [jev-commit](https://github.com/valentynkit/jev-commit) asks Jev whether a commit message matches the staged diff, and blocks the commit only when it finds a leaked credential.
- [jev.nvim](https://github.com/valentynkit/jev.nvim) splits the buffer into functions with Treesitter, has Jev score each one against a plain-language question, and lists the answers in quickfix ranked by probability.
- [jev-skip](https://github.com/valentynkit/jev-skip) reads YouTube's caption track and paints a per-segment sponsor probability on the seek bar before the intro ends, with no crowd database.
- [jev-plays-pokemon-red](https://github.com/valentynkit/jev-plays-pokemon-red) plays Pokemon Red on PyBoy, calling Jev only at route branches and scoring its faint predictions against the RAM state with Brier.

## License

This repository’s original list content and documentation are licensed under the [MIT License](LICENSE). Linked projects and third-party materials remain subject to their respective licenses; this license does not grant rights to them.
