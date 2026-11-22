# swift-site-build

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/YanaJeferson/swift-site-build/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/YanaJeferson/swift-site-build/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A faster drop-in for makefun-site 1.0.0: it writes the same static-site output tree, byte for byte, with less CPU.

## Run it

```sh
mkdir -p out
MAKEFUN_INPUT_DIR=/input MAKEFUN_OUTPUT_DIR=out node main.ts
```

`solve.js` exports `run(input)`; the driver reads `/input/cases.json` and writes `/output/answers.json`. The generator's own semantics live in `vendor/makefun-site/`, derived from metalsmith 2.7.0 and marked 18.2.1 under MIT (see `NOTICE`).

---

<sub>Entered on [make.fun](https://make.fun/?ref=r2p9j2t2&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
