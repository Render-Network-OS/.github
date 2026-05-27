# Crabbox

Use Crabbox for remote Linux verification.

Workflow:
- Warm early: crabbox warmup
- Reuse the returned slug for interactive checks and keep the cbx_ id in scripts/logs.
- Run checks with crabbox run --id <slug> -- <command>.
- Use crabbox status --id <slug> --wait before broad gates if needed.
- Use crabbox ssh --id <slug> to inspect the runner when a failure needs live context.
- Stop with crabbox stop <slug> when finished.

Do not debug product failures on a reused box that fails sync sanity. Stop it, warm a fresh box, and rerun.
