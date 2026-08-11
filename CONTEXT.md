# Pi Everforest

A theme extension for the pi coding agent, packaging the six sainnhe/everforest color schemes as installable pi themes.

## Language

### 上游配色

**scheme**:
六套配色组合之一，由 variant × contrast 决定（如 `everforest-dark-medium`）。
_Avoid_: 主题、配色方案（指上游组合时）

**variant**:
明暗色系，`dark` 或 `light`。

**contrast**:
背景对比度，`hard`、`medium` 或 `soft`（medium 为上游默认）。

**palette**:
上游 sainnhe/everforest 的官方色值集合，分 `palette1`（背景）与 `palette2`（前景）两个子表。

### pi 侧概念

**theme**:
pi 主题扩展中的一个 JSON 文件（`vars` + `colors` + 可选 `export`），与某个 scheme 一一对应。
_Avoid_: scheme（指 pi 文件时）

**token**:
pi 主题 `colors` 中的具名颜色槽位（如 `accent`、`toolTitle`），语义由 pi 固定。
