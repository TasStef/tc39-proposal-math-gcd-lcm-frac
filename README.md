# Math.gcd(), Math.lcm(), and Math.frac()

A Stage 0 ECMAScript proposal to add basic numeric utilities to the Math object.

- Live spec: [GitHub Pages](https://tasstef.github.io/tc39-proposal-math-gcd-lcm-frac)
- Author: Tasos Stefanidis (independent contributor)
- Stage: 0

## Motivation

JavaScript's Math object currently lacks several small, deterministic numeric utilities that exist in other languages. Adding them improves readability, reduces errors, and avoids repetitive user-space implementations.

## Examples

```js
Math.gcd(8,12); // 4
Math.lcm(4,6);  // 12
Math.frac(8.345); // 0.345
jjj
You can browse the [ecmarkup output](https://ACCOUNT.github.io/PROJECT/)
or browse the [source](https://github.com/ACCOUNT/PROJECT/blob/HEAD/spec.emu).
