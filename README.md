# Command Line Interfaces and Scripting — Staff Graded Assignment-1

**Name:** Kushagra Aggarwal

**Roll Number:** 2025EB01555

**Modules Covered:** 1–4

## Overview
This repository contains the complete submission for the Graded Lab Assignment covering Linux environment verification, permissions, file system links, I/O operations, and storage assessment. Each question is documented with the commands executed, their outputs, screenshots, and brief explanations of observations.

## Repository Structure

| Folder | Topic | Report File |
|---|---|---|
| `Q1-Environment/` | Linux Environment Verification | `Environment_Report.txt` |
| `Q2-Workspace/` | Secure Project Workspace Setup | `Project_Workspace_Report.txt` |
| `Q3-Links/` | File System and Link Analysis | `Link_Analysis_Report.txt` |
| `Q4-IO/` | File Access and I/O Investigation | `IO_Investigation_Report.txt` |
| `Q5-Storage/` | Storage Health Assessment (via vi) | `Storage_Assessment_Report.txt` |

Each folder contains:
- The report file with commands, outputs, and explanations
- Screenshots of command execution/output
- Any supporting files generated during the task (e.g. test files, links, workspace directories)

## Summary of Each Task

**Q1 — Environment Verification:** Checked user identity, group memberships, shell, working directory, and network connectivity.

**Q2 — Secure Workspace Setup:** Created a project directory structure and applied restrictive permissions (750/640) with explicit ownership to protect project data.

**Q3 — Link Analysis:** Investigated inode behavior by creating a hard link and symbolic link, then observed how each behaves when the original file is deleted.

**Q4 — I/O Investigation:** Examined open file descriptors, tested stdout/stderr redirection, and reviewed process resource limits (ulimit).

**Q5 — Storage Assessment:** Assessed available storage devices, mounted filesystems, disk/inode usage, and documented findings using the vi editor.

## Environment
Commands were executed on macOS (zsh shell). Where macOS lacks a direct Linux equivalent (e.g. `/proc`, `lsblk`, `free`), the closest macOS alternative was used and noted in the relevant report (e.g. `lsof`, `diskutil list`, `vm_stat`).
