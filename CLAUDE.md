# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

"Añade Swap a un sistema CoreOS" — a script + systemd unit to add a swap file to a CoreOS system (which ships without swap support out of the box).

## Layout

- `createswap` — creates and enables the swap file.
- `swap.service` — systemd unit to enable swap at boot.
