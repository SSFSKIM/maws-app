# maws-app

The code of MAWS, a desktop workspace for AI agents, published so its macOS tests can run on GitHub's hosted Macs.

Development happens in a private repository. Each commit here is a copy of one private commit's tree, made by a
deterministic filter; its message names the source commit, the source tree and the filter version. This repository
takes no issues or pull requests.

The instructions in `CLAUDE.md`, the charter and the plans assume the private repository's CI (`scripts/ci-gate.sh`,
the self-hosted lanes); here, only `.github/workflows/mac-e2e.yml` runs.

No license is granted: all rights reserved.
