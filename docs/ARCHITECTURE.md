# Flagship Architecture Overview

## offsec-mcp

Authorized target -> scope guard -> MCP tool layer -> recon/security analysis -> structured result.

The scope guard is a mandatory boundary before security tooling is exposed to an AI client.

## vigil

Pull request -> GitHub Action -> diff extraction -> security analysis -> findings -> severity gate -> PR feedback.

## mcpscan

MCP server -> tool metadata and instruction inspection -> security checks -> findings -> report.

## specter

Authorized target -> scope validation -> reconnaissance planning -> bounded tool execution -> analysis -> severity-graded report.

## Design principles

Across the projects, the common priorities are explicit authorization boundaries, bounded automation, reproducibility, and actionable output.
