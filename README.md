# Pomegranate Finance UIkit

Pomegranate Finance UIkit is a set of React components and hooks used to build pages on Pomegranate apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @pomeexchange/uikit`


### Theme

Before using Pomegranate Finance UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@pomeexchange/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@pomeexchange/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [GitHub Repository](https://github.com/pomeexchange/uikit)
