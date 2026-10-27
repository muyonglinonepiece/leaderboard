# U2Med · hermes · openai/deepseek-flash

Submitted: 2026-10-27 · chi-bench chi-bench-v1.0.0 · pass@1: **40.0%**

| Domain | pass@1 | n_trials |
|---|---|---|
| cm | 28.0% | 25 |
| pa_provider | 64.0% | 25 |
| pa_um | 28.0% | 25 |

Inspect a trajectory:

    zstdcat trials/cm/<trial_id>/agent/trajectory.jsonl.zst | jq .

See `submission.json` for the full manifest, `provenance.json` for reproducibility info.
