```
uv run python -m entrypoints.rosters_raw_html
uv run python -m entrypoints.parse_rosters
```

Supporting data:

- `_parsed-data/2026-state-qualifiers.json`: List of all state placers from
  2026, indexed by USAW number
- `_parsed-data/male-female.json`: Mapping by USAW number to gender (Male /
  Female)
- `_parsed-data/rosters.json`: "Living" document of club rosters throughout the
  season
