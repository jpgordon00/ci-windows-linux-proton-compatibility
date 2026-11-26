# What breaks when the same open game runs through Proton?

Compare the same redistributable Windows build on Windows and Proton, with a native Linux build as a reference.

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/windows-linux-proton-compatibility/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-windows-linux-proton-compatibility/pulls)

## Why this matters

Valve’s Proton release notes document launch, controller and frame-pacing fixes. An open game with a fixed scene makes regressions easier to reproduce and share.

## What to contribute

Choose a redistributable game that exports native Windows and Linux builds from the same source revision. Use a scripted path and fixed inputs to check launch, controller mapping and one streaming transition on all three configurations.

## How reviewers check it

Publish versions, build hashes, OS and driver details, a pass or fail for each check and reproducible steps for one difference. Use the same in-engine frame-time definition for cross-platform comparisons.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/windows-linux-proton-compatibility
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

See the [contribution ledger](https://works-by-us.jacob-gordon255689.chatgpt.site/api/problems/windows-linux-proton-compatibility/contributions) for merged proposals and available attribution.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-windows-linux-proton-compatibility/security/advisories/new) for security reports.

## Sources

- [Valve Proton changelog](<https://github.com/ValveSoftware/Proton/wiki/Changelog>)
- [Godot exporting documentation](<https://docs.godotengine.org/en/stable/tutorials/export/exporting_projects.html>)
