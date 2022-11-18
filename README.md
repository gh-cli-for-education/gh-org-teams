# gh extension

to install the extension, run:

```bash
gh extension install gh-cli-for-education/gh-org-teams
```

## Usage

```
 gh org-teams -h
Usage:
  /Users/casianorodriguezleon/.local/share/gh/extensions/gh-org-teams/gh-org-teams [-o|--ORG <ORG>]

For a better experience:
  set alias pwd to:  !gh config get current-org
  set alias cd to:   !gh config set current-org  2>/dev/null
```

## Example

```bash
 ✗ gh org-teams | jq '.data.organization.teams.edges | [ .[] | .node.name ]'
[
  "ale_hernandez_liberon-alu0101225562",
  "casiano-rodriguez-leon-alumnoudv4",
  "casiano-rodriguez-leon-crguezl",
  "claudio_nestor-yanes-mesa-alu0101229942",
  "jordi-bas-balcells-alu100965315",
  "parallel-computing-group-parallel",
  "santiago-villar-vazquez-alu0100990522"
]
```