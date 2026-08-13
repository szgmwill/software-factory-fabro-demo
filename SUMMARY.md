# Summary

This repository is a minimal Fabro project (a demo of the Fabro workflow
engine). It contains no application source code or README — only a `.fabro/`
configuration directory. `.fabro/project.toml` defines the project settings,
with auto-creation of draft pull requests enabled for successful workflow
runs. The single workflow lives under `.fabro/workflows/hello/` and is
described by `workflow.fabro`, a small directed graph that starts, greets the
user (asking the agent to introduce itself as a test of the engine), and
exits. The repo's only commit adds this initial Fabro project configuration.
