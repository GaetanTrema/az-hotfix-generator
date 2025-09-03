# Azure DevOps Hotfix work item creator

## Description

This script creates a new "Bug" work item and a matching branch in the current git repository.

## Installation

[Download](https://github.com/GaetanTrema/az-hotfix-generator/releases) the latest version of the script and move it to a directory within your PATH.

```sh
mv azhotfix /usr/local/bin
```

Create and fill the .env.hotfix file by copying the .env.hotfix.dist file.

## Usage

You must be logged in with `az login` in order to run this command.

```sh
azhotfix --title "The work item title" --description "This text will fill the Steps-to-Reproduce field"
```
