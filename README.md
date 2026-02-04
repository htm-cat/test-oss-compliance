# test-oss-compliance
# OSS compliance test repo

This repo tests org/oss-compliance reusable workflows.

## How to test
1) Open a PR that introduces `pm2` (AGPL) -> expect failure.
2) Open a PR that only has `express` -> expect success.

Test Node 8