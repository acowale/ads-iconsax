<h1 align="center">@acowale/ads-iconsax</h1>

<p align="center">
  Iconsax icon pack for React |
1000 icons in 6 different styles |
24px grid-based
<p>

<br>

## Installation

This package is published to GitHub Packages, so the `@acowale` scope needs to point
at that registry first:

```bash
npm config set @acowale:registry https://npm.pkg.github.com
```

Then install (use `pnpm` — the npm client has failed on this package):

```bash
pnpm add @acowale/ads-iconsax
```

## Usage

```jsx
import React from 'react';
import { Home } from '@acowale/ads-iconsax';

const Example = () => {
  // then use it as a normal React Component
  return <Home />;
};
```

You can configure icons with inline props:

```jsx
<Home color="#eee" variant="Bold" size={54} />
```

## Props

| Prop      | Type                                                | Default        | Note                   |
| --------- | --------------------------------------------------- | -------------- | ---------------------- |
| `color`   | `string`                                            | `currentColor` | css color              |
| `size`    | `number` `string`                                   | 24px           | size={24} or size="24" |
| `variant` | `Linear` `Outline` `TwoTone` `Bulk` `Broken` `Bold` | `Linear`       | icons styles           |

---

## Attribution

Fork of [iconsax-react](https://github.com/rendinjast/iconsax-react) by Erfan Khadivar,
published under the `@acowale` scope for internal use. Artwork from the Iconsax icon set.

## License

[MIT](./LICENSE)
