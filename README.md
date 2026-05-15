# Log rotation script

## Task
Write a Bash script to rotate log files when they exceed a size threshold. Document a `cron` example in this README or in `cron.example`.

## Starter (not finished)
`rotate_logs.sh` must be implemented before CI smoke tests pass.

## Your work
- Implement size-based rotation (rename + truncate or copy-truncate).
- Add `cron.example` with a schedule (e.g. daily).
- Test against a sample log under `sample/app.log`.
