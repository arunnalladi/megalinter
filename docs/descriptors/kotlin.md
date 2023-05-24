---
title: KOTLIN linters in MegaLinter
description: ktlint is available to analyze KOTLIN files in MegaLinter
---
<!-- markdownlint-disable MD003 MD020 MD033 MD041 -->
<!-- @generated by .automation/build.py, please don't update manually -->
<!-- Instead, update descriptor file at https://github.com/oxsecurity/megalinter/tree/main/megalinter/descriptors/kotlin.yml -->
# KOTLIN

## Linters

| Linter                                                                 | Additional                                                                                                                                                                                                                          |
|------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [**ktlint**](kotlin_ktlint.md)<br/>[_KOTLIN_KTLINT_](kotlin_ktlint.md) | [![GitHub stars](https://img.shields.io/github/stars/pinterest/ktlint?cacheSeconds=3600)](https://github.com/pinterest/ktlint) ![autofix](https://shields.io/badge/-autofix-green) ![sarif](https://shields.io/badge/-SARIF-orange) |

## Linted files

- File extensions:
  - `.kt`
  - `.kts`

## Configuration in MegaLinter

| Variable                    | Description                   | Default value |
|-----------------------------|-------------------------------|---------------|
| KOTLIN_FILTER_REGEX_INCLUDE | Custom regex including filter |               |
| KOTLIN_FILTER_REGEX_EXCLUDE | Custom regex excluding filter |               |


## Behind the scenes

### Installation

- APK packages (Linux):
  - [openjdk11](https://pkgs.alpinelinux.org/packages?branch=edge&name=openjdk11)