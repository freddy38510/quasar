---
title: Button Group
desc: The QBtnGroup Vue component groups QBtn and QBtnDropdown into a single unit.
keys: QBtnGroup
examples: QBtnGroup
related:
  - /vue-components/button
  - /vue-components/button-dropdown
  - /vue-components/button-toggle
---

You can conveniently group [QBtn](/vue-components/button) and [QBtnDropdown](/vue-components/button-dropdown) using QBtnGroup. Be sure to check those component's respective pages to see their props and methods.


<doc-api file="QBtnGroup" />

## Usage
<doc-example title="Examples" file="Group" />

::: warning
You must use same design props (flat, outline, push, ...) on both the parent QBtnGroup and the children QBtn/QBtnDropdown.
:::

<doc-example title="Spread horizontally" file="GroupSpread" />

<doc-example title="With QBtnDropdown" file="WithDropdown" />
