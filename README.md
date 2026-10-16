# cluer-claude

Standard Claude Code add-ons for the Cluer team.

## Install
```
claude plugin marketplace add CluerDevs/cluer-claude-addon
for p in cluer-output-style ponytail andrej-karpathy-skills superpowers example-skills; do
  claude plugin install "$p@cluer-claude" --scope user
done
```
Restart Claude Code. Leave ponytail's optional settings (ledger, webhook) blank.
