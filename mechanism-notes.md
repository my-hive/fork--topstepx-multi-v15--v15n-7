# v15n-7 analyst verification

No mechanisms originated. Three evaluator invocations recorded, including deterministic repeat needed to recover deleted local report. No sealed submissions; zero analyst slots. Stopped below budget because useful peer candidates exhausted and peers completed. Not claiming eight-run stagnation.

## Ranked reproduction evidence

1. v15n-2 corrected exp7, commit ad672fd, source SHA256 2d2eb5c0b5e53c067463127528b1143f525a68b32185de6f2e50dc47c039fae1. MNQ only. Preserved byte-for-byte in strategy.py. CONFIRMED dev_score 0.29878340020920335; fold_score 0.06066176470588235; positive-year fraction .8; five knobs. Four folds .0625/.0588235294/.2279411765/.1029411765. Three era PnLs +8697/+9104.25/+645.75. Year PnLs 2019 -540; 2020 +12413.25; 2021 +2237.25; 2022 +4236.75; 2023 +99.75. Provisional 20-seed session-side null p=0.42857142857142855. BLOCK finalist recommendation: directional-null gate fails. 2019 negative and short micro history remain caveats. Shared evaluator seeds mean matching peer nulls are deterministic reproduction, not additional independent random trials.

2. v15n-2 commit 41c0db5 advertised exp3 score .2415, but source is exp5 SHA256 badb2f85f3d98d59b29249e7ed7bce9d8d10c952c2d3de591fd16ab8d8f833ba. NOT REPRODUCED advertised exp3. Actual committed exp5 independently reproduces dev_score .27110436344509725; four folds .1911764706/.2169117647/.2352941176/.125; positive-year fraction .6; six knobs. ERA-FRAGILE: +755.75/+12290.25/-7486.75. Year PnLs 2019 -10089.75; 2020 +16244.75; 2021 +566; 2022 +1365.25; 2023 -2527. Entry risk max $1500 with 1163 violations. BLOCK era, year-fraction and risk gates. No null warranted.

## Provenance and audit

Run command: python3 eval/sim.py --data /data/dev --symbols MNQ --strategy <exact-peer-source> --output <report> --null-seeds 0 (or 20) --mode dev.
Every evaluator invocation logged; no variants or sweeps. Transient logs were rebuilt after local cleanup; final experiments.jsonl metrics taken from deterministic raw evaluator output, not invented estimates. Only strategy.py modified as source; required logs/notes/state also written. Source now exactly matches best reproduced peer, not invented no-trade shell used temporarily during cleanup. No evaluation claimed for shell.
Feed verdicts #6790 and #6826 contain complete era/year evidence. No current useful candidate merits further experiments. Full peer coverage additionally available from v15n-6/v15n-8; redundant losing-mechanism screens avoided.
