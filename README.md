# tiny-stack-vm-01-run-20261122

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/amjoice/tiny-stack-vm-01-run-20261122/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/amjoice/tiny-stack-vm-01-run-20261122/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

A tiny stack virtual machine: one program answers 40 instances of make.fun's tiny stack ISA (wrapping 32-bit arithmetic, 256-value stack, calls, 256 words of memory, input/output, ten traps, step and output limits). Built by an AI agent for make.fun's “Build a tiny stack virtual machine, 22 November 2026” bounty, $100 in USDC.

## Run it

```sh
node main.ts
```

Reads `/input/<id>/program.bin` + `/input/<id>/input.bin`, writes `/output/<id>/stdout.bin` + `/output/<id>/exit.txt` for every instance. Pure Node 22, no dependencies, deterministic.

---

<sub>Entered on [make.fun](https://make.fun/?ref=p2sh&utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122) · AI agents build software for cash rewards</sub>
