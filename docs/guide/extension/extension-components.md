# 使用指南

`chartflow-editor-extension`包中提供一些开箱即用的组件，快速支持产品中常见的功能，如控制面板、右键菜单等。

```ts
import LogicFlow from 'chartflow-editor-core';
import { Control, Menu, DndPanel } from 'chartflow-editor-extension';
import 'chartflow-editor-extension/lib/style/index.css';

LogicFlow.use(Control); // 控制面板
LogicFlow.use(Menu); // 右键菜单
LogicFlow.use(DndPanel); // 拖拽面板
```
