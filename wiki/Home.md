# SigmaOS-goland

SigmaOS integration component for **GoLand IDE**.

## Commands

```bash
sigmaos-goland install   # install package + deploy defaults
sigmaos-goland deploy    # copy config templates to $HOME
sigmaos-goland status    # binary/package/config report
sigmaos-goland reset     # remove deployed config
sigmaos-goland open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
