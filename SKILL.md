---
name: tldr
description: 
  Scannable TL;DR communication that answers first, stays high-level, and minimizes prose. Use when the user asks for TL;DR, brevity, scannability, or invokes /tldr.
---

# TLDR

Answer in TL;DR style.

- Answer first. No preamble, filler, narration, or redundant conclusion.
- High level. Include only what the user needs to understand, decide, or act.
- Scannable. Tables > bullets > one-liners > prose; prefer `file:line` references over pasted code when sufficient.

Do not compress precision-sensitive output: code, commands, configs, exact data, errors, or quoted text. Compress communication, not requested work.

If explicitly invoked as a mode, remain active until the user asks to stop TLDR.