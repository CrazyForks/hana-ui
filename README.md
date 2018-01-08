# hana-ui

A React UIKit with nijigen style.

[Home page is coming soon !](https://hana-ui.moe)

## Guide

hana-ui is a completed UI component libray which almost base components that you may use in development works, and it also easy to use in your page.

### Install

```bash
npm install hana-ui

// or

yarn add hana-ui
```

### Usage

#### import hana-ui in your page

Example:

```javascript
import React from 'react';
import {Button} from 'hana-ui';
// or just import Button
import Button from 'hana-ui/dist/seeds/Button';

export default () => (
  <Button size={'middle'}>
    Touch me...
  </Button>    
);
```

More components usage please checkout [Documents](https://hana-ui.moe/en/document) page.

## Contribution

Change the world with hana.

### How

You could contribute to hana-ui in may ways, hana needs your help.

#### Tell to us

1. Open the project [hana-ui](https://github.com/hana-group/hana-ui) on Github.
2. Submit your **issue** with detailed description, code and error stack.
3. We will have a discussion and find the way to fix bugs. 
4. Bugs are fixed.

#### Fix by yourself

1. Open the project [hana-ui](https://github.com/hana-group/hana-ui) on Github.
2. Fork it and fix bugs in a new branch.
3. Open a **pull request** with detailed description such as information, scope of influence...
4. We will review changes and merge it to master branch.

### Scripts

Following npm scripts may help you while developing.

**1. Develop:**

```bash
npm run dev
```

Then open the **8000** port and preview the demo.

**1. Prebuilt:**

```bash
npm run build
```

Compile source code to **dist** folder with es5.

## License

hana-ui is an open-source project with [MIT](https://opensource.org/licenses/MIT) license by [hana-group](https://github.com/hana-group).  

Welcome to join us !