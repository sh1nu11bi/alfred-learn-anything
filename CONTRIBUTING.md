# Contributing to Alfred Learn Anything
There are many ways you can contribute. You can:
- Make suggestions and file bugs in [Issues](../../issues/).
- Fix issues and add features to the workflow with [Pull Requests](../../pulls/).
- Improve [Learn anything](https://learn-anything.xyz/) and its [curated lists](https://github.com/learn-anything/curated-lists#readme) that the workflow searches over.

## Dependencies
The workflow is written in [Go language](https://golang.org/) and uses [AwGo](https://github.com/deanishe/awgo) library for all the Alfred related things.

## Developing the workflow
If you want to add features and things to the workflow.

It is best to use [Alfred CLI tool](https://godoc.org/github.com/jason0x43/go-alfred/alfred) which you can install by running:

`go install github.com/jason0x43/go-alfred/alfred`

You can then clone this repository and run: `alfred link` inside it. This will make a symbolic link of the [`workflow`](workflow) directory.

You can then make changes to the code and after run `alfred build` to build the go binary to `workflow` directory. Which you can then call from inside Alfred [Script Filters](https://www.alfredapp.com/help/workflows/inputs/script-filter/).

I also wrote about my own process in making Alfred workflows [here](https://wiki.nikitavoloboev.xyz/macOS/apps/alfred/making-workflows.html).

## Submitting a Pull Request
Please go through [existing issues](../../issues/) and [pull requests](../../pulls/) to check if somebody else is already working on the issue.

#### Thank you for taking the time to contribute! 💜