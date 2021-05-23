# 🥞 RareSwap UIkit

[![Version](https://img.shields.io/npm/v/@rareswap/uikit)](https://www.npmjs.com/package/@rareswap/uikit) [![Size](https://img.shields.io/bundlephobia/min/@rareswap/uikit)](https://www.npmjs.com/package/@rareswap/uikit)

RareSwap UIkit is a set of React components and hooks used to build pages on RareSwap's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @rareswap/uikit`

## Setup

### Theme

Before using RareSwap UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@rareswap/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@rareswap/uikit'
...
<ResetCSS />
```
