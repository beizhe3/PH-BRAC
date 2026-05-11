# Reproduction Plan

This document outlines the planned release sequence for reproducing the PH-BRAC study analyses.

## Phase 1: Repository Setup

- Create the public repository structure
- Add preliminary documentation
- Add provisional package requirements
- Do not release study data or reproduction scripts until institutional review is complete

## Phase 2: Data and Split Release

- Add anonymized feature-level data
- Add data dictionary and feature descriptions
- Add training, validation, and testing split files
- Document file checksums and expected row counts

## Phase 3: Reproduction Scripts

- Add preprocessing scripts
- Add model training scripts
- Add evaluation scripts
- Add scripts for tables and figures
- Add command-line examples for reproducing the main results

## Planned Environment

The provisional Python dependencies are listed in `requirements.txt`. Exact version pins will be added with the reproduction scripts.

## Planned Validation

The final reproduction release will include expected metrics, output file names, and checksums where appropriate so that users can verify their results against the published study.
