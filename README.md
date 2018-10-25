# `@rehooks/document-visibility`

> React hook for subscribing to document visibility

> **Note:** This is using the new [React Hooks API Proposal](https://reactjs.org/docs/hooks-intro.html)
> which is subject to change until React 16.7 final.
>
> You'll need to install `react`, `react-dom`, etc at `^16.7.0-alpha.0`

## Install

```sh
yarn add @rehooks/document-visibility
```

## Usage

```js
import useDocumentVisibility from '@rehooks/document-visibility';

function MyComponent() {
  let documentVisibility = useDocumentVisibility();
  // documentVisibility = "hidden" | "visible" | "prerender"

  // ...
}
```
