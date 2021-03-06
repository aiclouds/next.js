# Example app with [glamorous](https://github.com/kentcdodds/glamorous)

## How to use

> Glamorous is no longer maintained. Choose styled-components or emotion instead

### Using `create-next-app`

Execute [`create-next-app`](https://github.com/zeit/next.js/tree/canary/packages/create-next-app) with [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) or [npx](https://github.com/zkat/npx#readme) to bootstrap the example:

```bash
npx create-next-app --example with-glamorous with-glamorous-app
# or
yarn create next-app --example with-glamorous with-glamorous-app
```

### Download manually

Download the example:

```bash
curl https://codeload.github.com/zeit/next.js/tar.gz/canary | tar -xz --strip=2 next.js-canary/examples/with-glamorous
cd with-glamorous
```

Install it and run:

```bash
npm install
npm run dev
# or
yarn
yarn dev
```

Deploy it to the cloud with [now](https://zeit.co/now) ([download](https://zeit.co/download))

```bash
now
```

## The idea behind the example

This example features how to use [glamorous](https://github.com/kentcdodds/glamorous) as the styling solution instead of [styled-jsx](https://github.com/zeit/styled-jsx). It also incorporates [glamor](https://github.com/threepointone/glamor) since `glamor` is a dependency for `glamorous`.

We are creating three `div` elements with custom styles being shared across the elements. The styles includes the use of pseudo-elements and CSS animations.
