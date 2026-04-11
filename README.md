# Caveman Lite

Terse like caveman. ~50% token savings. Technical exact.

## Install

```bash
npx skills add yourusername/caveman-lite -a opencode
```

Or from local clone:
```bash
npx skills add /path/to/caveman-lite -a opencode
```

## Usage

**Default**: Terse caveman style. Every response.

**Verbose mode**: Add `verbose` anywhere in your message:

```
verbose: explain how this works
```

## Before/After

| Normal (72 tokens) | Caveman Lite (31 tokens) |
|-------------------|------------------------|
| "The reason your React component is re-rendering is likely because you're creating a new object reference on each render cycle. When you pass an inline object as a prop, React's shallow comparison sees it as a different object every time, which triggers a re-render." | "New object ref each render. Inline object prop = new ref = re-render. Wrap in `useMemo`." |

## Uninstall

```bash
npx skills remove caveman-lite
```

## License

MIT