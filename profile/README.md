<!-- Generated from projects.json by ofam-site -profile; edit the data, then regenerate. -->

<p align="center">
  <a href="https://ofam.dev"><picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://ofam.dev/img/o-family/logo-animated-dark.svg">
    <img src="https://ofam.dev/img/o-family/logo-animated-light.svg" alt="o-family" width="360">
  </picture></a>
</p>

# o-family

Modal, Vim-like terminal tools and libraries in Go, built on an extensible command model: keys are data, and every action is a command you can also run from the shell.

[Visit ofam.dev](https://ofam.dev) for the projects, documentation and key references.

<p align="center">
  <a href="https://github.com/ofamtools/ochazuke" title="ochazuke"><img src="https://ofam.dev/img/ochazuke/icon-animated.svg" width="40" height="40" alt="ochazuke"></a>
  <a href="https://github.com/ofamtools/oden" title="oden"><img src="https://ofam.dev/img/oden/icon-animated.svg" width="40" height="40" alt="oden"></a>
  <a href="https://github.com/ofamtools/matomeru" title="matomeru"><img src="https://ofam.dev/img/matomeru/icon-animated.svg" width="40" height="40" alt="matomeru"></a>
  <a href="https://github.com/ofamtools/o-cmds" title="o-cmds"><img src="https://ofam.dev/img/o-cmds/icon-animated.svg" width="40" height="40" alt="o-cmds"></a>
  <a href="https://github.com/ofamtools/o-questions" title="o-questions"><img src="https://ofam.dev/img/o-questions/icon-animated.svg" width="40" height="40" alt="o-questions"></a>
  <a href="https://github.com/ofamtools/o-lane" title="o-lane"><img src="https://ofam.dev/img/o-lane/icon-animated.svg" width="40" height="40" alt="o-lane"></a>
  <a href="https://github.com/ofamtools/o-gh" title="o-gh"><img src="https://ofam.dev/img/o-gh/icon-animated.svg" width="40" height="40" alt="o-gh"></a>
  <a href="https://github.com/ofamtools/monogatari" title="monogatari"><img src="https://ofam.dev/img/monogatari/icon-animated.svg" width="40" height="40" alt="monogatari"></a>
  <a href="https://github.com/ofamtools/o-json" title="o-json"><img src="https://ofam.dev/img/o-json/icon-animated.svg" width="40" height="40" alt="o-json"></a>
  <a href="https://github.com/ofamtools/nabe" title="nabe"><img src="https://ofam.dev/img/nabe/icon-animated.svg" width="40" height="40" alt="nabe"></a>
  <a href="https://github.com/ofamtools/o-csv" title="o-csv"><img src="https://ofam.dev/img/o-csv/icon-animated.svg" width="40" height="40" alt="o-csv"></a>
  <a href="https://github.com/ofamtools/o-df" title="o-df"><img src="https://ofam.dev/img/o-df/icon-animated.svg" width="40" height="40" alt="o-df"></a>
  <a href="https://github.com/ofamtools/o-ai" title="o-ai"><img src="https://ofam.dev/img/o-ai/icon-animated.svg" width="40" height="40" alt="o-ai"></a>
  <a href="https://github.com/ofamtools/o-fleet" title="o-fleet"><img src="https://ofam.dev/img/o-fleet/icon-animated.svg" width="40" height="40" alt="o-fleet"></a>
  <a href="https://github.com/ofamtools/o-md" title="o-md"><img src="https://ofam.dev/img/o-md/icon-animated.svg" width="40" height="40" alt="o-md"></a>
  <a href="https://github.com/ofamtools/o-mermaid" title="o-mermaid"><img src="https://ofam.dev/img/o-mermaid/icon-animated.svg" width="40" height="40" alt="o-mermaid"></a>
  <a href="https://github.com/ofamtools/o-modal" title="o-modal"><img src="https://ofam.dev/img/o-modal/icon-animated.svg" width="40" height="40" alt="o-modal"></a>
</p>

## Start with the o command

`o` is the family's root command, and every tool you add is one of its commands. With it installed you don't need the dash: `o gh` runs `o-gh`, `o md` runs `o-md`.

**1 · install o**

```sh
go install ofam.dev/oden/cmd/o@latest
```

`o NAME` runs the `o-NAME` executable on your PATH with every argument passed through: `o gh`, `o md plan.md`, `o lane ...`. A unique prefix is enough. `o` with no arguments, or `o help`, lists the tools it finds.

**2 · add a tool**

```sh
go install ofam.dev/o-gh@latest
o gh
```

Every `o-*` tool installs the same way and is then a command of `o`. The projects below give each one's install line.

## Libraries

### <img src="https://ofam.dev/img/ochazuke/icon-animated.svg" width="28" height="28" alt=""> ochazuke

A modal TUI framework for Go, built on Bubble Tea v2: Vim-style modes and an extensible command model, so every action in your app can be bound to a key, run from the palette or scripted from the shell.

[ofam.dev](https://ofam.dev/ochazuke/) · [GitHub](https://github.com/ofamtools/ochazuke)

```sh
go get ofam.dev/ochazuke@latest
```

### <img src="https://ofam.dev/img/oden/icon-animated.svg" width="28" height="28" alt=""> oden

Subcommand dispatch for Go CLIs: a bin's inline commands and every `<bin>-<sub>` executable on PATH, in one table, resolved by name, alias or unique prefix.

[ofam.dev](https://ofam.dev/oden/) · [GitHub](https://github.com/ofamtools/oden)

```sh
go install ofam.dev/oden/cmd/o@latest
```

```sh
go get ofam.dev/oden@latest
```

### <img src="https://ofam.dev/img/monogatari/icon-animated.svg" width="28" height="28" alt=""> monogatari

An ochazuke testing library: stories are JSON keystroke scripts played headless against your app's real UI, with expectations on what the screen shows.

[ofam.dev](https://ofam.dev/monogatari/) · [GitHub](https://github.com/ofamtools/monogatari)

```sh
go get ofam.dev/monogatari@latest
```

### <img src="https://ofam.dev/img/o-modal/icon-animated.svg" width="28" height="28" alt=""> o-modal

A proof of concept: a modal key engine for Go. Keys in, steps out; the host decides what runs.

[ofam.dev](https://ofam.dev/#project-o-modal) · [GitHub](https://github.com/ofamtools/o-modal)

```sh
go get ofam.dev/o-modal/modal@latest
```

## Apps

### <img src="https://ofam.dev/img/matomeru/icon-animated.svg" width="28" height="28" alt=""> matomeru

An extensible terminal workspace for coding agents: projects, tasks, notes, live agent panes, their turns and your reviews, gathered in one TUI.

[ofam.dev](https://ofam.dev/matomeru/) · [GitHub](https://github.com/ofamtools/matomeru)

```sh
go install ofam.dev/matomeru/cmd/mtm@latest
```

## Extensions

### <img src="https://ofam.dev/img/o-cmds/icon-animated.svg" width="28" height="28" alt=""> o-cmds

Saved shell scripts to list, inspect and run by name or number, with captured run history and a standalone TUI.

[ofam.dev](https://ofam.dev/#project-o-cmds) · [GitHub](https://github.com/ofamtools/o-cmds)

```sh
go install ofam.dev/oden/cmd/o@latest
go install ofam.dev/o-cmds@latest
```

### <img src="https://ofam.dev/img/o-questions/icon-animated.svg" width="28" height="28" alt=""> o-questions

A private journal of the owner's questions and the answers given, across agents, projects and sessions, with append-only threads and undo history.

[ofam.dev](https://ofam.dev/#project-o-questions) · [GitHub](https://github.com/ofamtools/o-questions)

```sh
go install ofam.dev/oden/cmd/o@latest
go install ofam.dev/o-questions@latest
```

### <img src="https://ofam.dev/img/o-lane/icon-animated.svg" width="28" height="28" alt=""> o-lane

Actor-attributed records for work lanes: nested lanes per project with lifecycle states, live pane and agent status, and undoable history, plus a Lanes page that mtm mounts.

[ofam.dev](https://ofam.dev/#project-o-lane) · [GitHub](https://github.com/ofamtools/o-lane)

```sh
go install ofam.dev/oden/cmd/o@latest
go install ofam.dev/o-lane@latest
```

### <img src="https://ofam.dev/img/o-gh/icon-animated.svg" width="28" height="28" alt=""> o-gh

GitHub pull requests on one page: yours, the ones waiting on your review, the ones you watch and the ones you ignore, read through the gh CLI, with new review requests and CI changes sent to the mtm inbox.

[ofam.dev](https://ofam.dev/#project-o-gh) · [GitHub](https://github.com/ofamtools/o-gh)

```sh
go install ofam.dev/oden/cmd/o@latest
go install ofam.dev/o-gh@latest
```

### <img src="https://ofam.dev/img/o-md/icon-animated.svg" width="28" height="28" alt=""> o-md

Markdown documents with item notes, a family extension for mtm.

[ofam.dev](https://ofam.dev/#project-o-md) · [GitHub](https://github.com/ofamtools/o-md)

```sh
go install ofam.dev/oden/cmd/o@latest
go install ofam.dev/o-md@latest
```

## Tools

### <img src="https://ofam.dev/img/o-json/icon-animated.svg" width="28" height="28" alt=""> o-json

A JSON structure and table viewer: every path with its types and counts, arrays of objects as tables, and restructure, query with jq and export.

[ofam.dev](https://ofam.dev/o-json/) · [GitHub](https://github.com/ofamtools/o-json)

```sh
go install ofam.dev/oden/cmd/o@latest
go install ofam.dev/o-json@latest
```

### <img src="https://ofam.dev/img/o-csv/icon-animated.svg" width="28" height="28" alt=""> o-csv

A CSV viewer built on ochazuke. Viewing comes first; editing is there but stays off until you ask for it.

[ofam.dev](https://ofam.dev/#project-o-csv) · [GitHub](https://github.com/ofamtools/o-csv)

```sh
go install ofam.dev/oden/cmd/o@latest
go install ofam.dev/o-csv@latest
```

### <img src="https://ofam.dev/img/o-df/icon-animated.svg" width="28" height="28" alt=""> o-df

Finds and clears the usual disk hogs on a Mac: package, browser and build caches, model downloads. Each culprit is a row of data.

[ofam.dev](https://ofam.dev/#project-o-df) · [GitHub](https://github.com/ofamtools/o-df)

```sh
go install ofam.dev/oden/cmd/o@latest
go install ofam.dev/o-df@latest
```

### <img src="https://ofam.dev/img/o-ai/icon-animated.svg" width="28" height="28" alt=""> o-ai

The local AI harnesses and their providers, models, skills, agents and settings, inspected without making a model request.

[ofam.dev](https://ofam.dev/#project-o-ai) · [GitHub](https://github.com/ofamtools/o-ai)

```sh
go install ofam.dev/oden/cmd/o@latest
go install ofam.dev/o-ai@latest
```

### <img src="https://ofam.dev/img/o-fleet/icon-animated.svg" width="28" height="28" alt=""> o-fleet

A registry of your machines and read-only checks across them, in parallel, over ssh.

[ofam.dev](https://ofam.dev/#project-o-fleet) · [GitHub](https://github.com/ofamtools/o-fleet)

```sh
go install ofam.dev/oden/cmd/o@latest
go install ofam.dev/o-fleet@latest
```

### <img src="https://ofam.dev/img/o-mermaid/icon-animated.svg" width="28" height="28" alt=""> o-mermaid

Converts Mermaid diagrams to SVG, PNG and HTML with the embedded Beautiful Mermaid engine, using headless Chrome; reached in mtm as `mtm mermaid`.

[ofam.dev](https://ofam.dev/#project-o-mermaid) · [GitHub](https://github.com/ofamtools/o-mermaid)

```sh
go install ofam.dev/oden/cmd/o@latest
go install ofam.dev/o-mermaid@latest
```

## Hosts

### <img src="https://ofam.dev/img/nabe/icon-animated.svg" width="28" height="28" alt=""> nabe

A host for ochazuke extensions (`o nabe`, `o tui`): any executable that answers `catalog` becomes a page.

[ofam.dev](https://ofam.dev/#project-nabe) · [GitHub](https://github.com/ofamtools/nabe)

```sh
go install ofam.dev/nabe@latest
```
