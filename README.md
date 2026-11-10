# aiball3d-blender-tests
Synthetic Blender headless testing

## Verified baseline — 2026-11-10

- **Run:** [Blender 5.2.4 synthetic smoke #1](https://github.com/garyforever247-ux/aiball3d-blender-tests/actions/runs/42881649432) — **success**, first attempt, manual `workflow_dispatch`.
- **Workflow commit tested:** [`2ca1f099a13dd141a770f3b3bcd912bb4b10ad70`](https://github.com/garyforever247-ux/aiball3d-blender-tests/commit/2ca1f099a13dd141a770f3b3bcd912bb4b10ad70).
- **Environment:** GitHub-hosted Ubuntu 24.04, x86_64; official Blender **5.2.4 LTS** in headless mode, bundled Python **3.13.13**.
- **Integrity:** Official manifest matched the owner-supplied SHA-256 pin; downloaded archive checksum verified before extraction.
- **Synthetic geometry:** cube with 8 vertices, 6 faces, dimensions `[2, 2, 2]`, volume approximately `8`; **passed**.
- **Execution:** Blender exit status `0`, elapsed `2.17 s`, peak RSS `308628 KiB` (approximately 301 MiB).
- **Evidence:** Run logs and seven bounded diagnostic files in the workflow artifact (GitHub retention: one day).

**Scope:** This is a baseline for the disposable cloud **Blender runtime and synthetic geometry only**. It does not validate any private AIBall3D code, Astra Bridge, real scenes, integration, Phase 0 benchmark, or release readiness. No source or assets from private repositories are included. Further workflow executions require separate authorization.
