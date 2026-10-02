# Pi Everforest

A theme extension for the pi coding agent, packaging the six sainnhe/everforest color schemes as installable pi themes.

## Language

### Upstream color schemes

**scheme**:
One of the six color combinations, determined by variant × contrast (e.g. `everforest-dark-medium`).
_Avoid_: theme, color scheme (when referring to an upstream combination)

**variant**:
The light or dark family, `dark` or `light`.

**contrast**:
The background contrast level: `hard`, `medium`, or `soft` (upstream default is medium).

**palette**:
The set of official color values from upstream sainnhe/everforest, split into two sub-tables: `palette1` (backgrounds) and `palette2` (foregrounds).

### pi-side concepts

**theme**:
A single JSON file inside the pi theme extension (`vars` + `colors` + optional `export`), in one-to-one correspondence with a scheme.
_Avoid_: scheme (when referring to a pi file)

**token**:
A named color slot in a pi theme's `colors` (e.g. `accent`, `toolTitle`); its semantics are fixed by pi.
