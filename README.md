# Next.js React TypeScript Snippets

Extended version of snippets for Next.js, React, TypeScript, TSX, and JSX in Zed.

## Included Scopes

- `snippets/javascript.json`
- `snippets/tsx.json`
- `snippets/typescript.json`

Zed uses `javascript.json` for JSX snippets, so the local `jsx.json` snippet file is published as `snippets/javascript.json` in this extension.

## Snippet Commands

### JavaScript / JSX

| Command | Snippet | Description |
| --- | --- | --- |
| `npage` | Next.js Page Component | Next.js page component |
| `nlayout` | Next.js Layout Component | Next.js Layout component |
| `apiroute` | Next.js API Route | Next.js API route handler |
| `middleware` | Next.js Middleware | Next.js Middleware |
| `nlink` | Next.js Link | Next.js Link component |
| `nimg` | Next.js Image | Next.js Image component |
| `rfc` | React Functional Component | React Functional Component |
| `rff` | React Functional Component (function) | React Functional Component (function declaration) |
| `us` | useState Hook | React useState Hook |
| `ue` | useEffect (with deps) | useEffect Hook |
| `uem` | useEffect (mount only) | useEffect runs once at mount |
| `uer` | useEffect (every render) | useEffect runs on every render |
| `cleanup` | useEffect Cleanup | useEffect cleanup function |
| `urf` | useRef | React useRef Hook |
| `uctx` | useContext | React useContext Hook |
| `ume` | useMemo | useMemo Hook |
| `ucb` | useCallback | useCallback Hook |
| `hk` | Custom Hook | Custom hook boilerplate |
| `rctx` | React Context | React Context with Provider and custom hook |
| `frag` | React Fragment | React Fragment shorthand |
| `apifetch` | Async fetch | Async/await fetch API call |
| `clg` | Console Log | console.log |

### TSX

| Command | Snippet | Description |
| --- | --- | --- |
| `npage` | Next.js Page Component | Next.js page component |
| `nlayout` | Next.js Layout Component | Next.js Layout component |
| `apiroute` | Next.js API Route | Next.js App Router API route handler |
| `middleware` | Next.js Middleware | Next.js Middleware |
| `nlink` | Next.js Link | Next.js Link component |
| `nimg` | Next.js Image | Next.js Image component |
| `rfc` | React Functional Component (const) | React Functional Component with TypeScript props |
| `rff` | React Functional Component (function) | React Functional Component (function declaration) |
| `frc` | ForwardRef Component | ForwardRef component with TypeScript props |
| `us` | useState Hook | useState Hook with TypeScript |
| `ue` | useEffect (with deps) | useEffect Hook |
| `uem` | useEffect (mount only) | useEffect Hook runs once at mount |
| `uer` | useEffect (every render) | useEffect Hook runs on every render |
| `cleanup` | useEffect Cleanup | useEffect cleanup function |
| `urf` | useRef | useRef Hook with TypeScript |
| `uctx` | useContext | useContext Hook |
| `ume` | useMemo | useMemo Hook |
| `ucb` | useCallback | useCallback Hook |
| `ur` | useReducer | useReducer Hook |
| `hk` | Custom Hook | Custom hook boilerplate |
| `rctx` | React Context | React Context with Provider and custom hook |
| `frag` | React Fragment | React Fragment shorthand |
| `nerror` | Next.js Error Boundary | Next.js error boundary client component |
| `clg` | Console Log | console.log |

### TypeScript

| Command | Snippet | Description |
| --- | --- | --- |
| `tst` | Type Alias | Type alias |
| `tsi` | Interface | Interface |
| `enum` | Enum | Enum |
| `tsfn` | Function Declaration | Function declaration with types |
| `tsafn` | Arrow Function | Arrow function with types |
| `tsfetch` | Typed Fetch Function | Typed fetch function with error handling |
| `tstc` | Try/Catch | try/catch with typed error |
| `tgf` | Type Guard | Type guard function |
| `tsrcd` | Record Type | Record utility type |
| `tscls` | Class with Constructor | Class with constructor |
| `tsserv` | Service Class | Service class boilerplate |
| `tsimprt` | Import Statement | Named import |
| `tsxprt` | Export Statement | Export members |
| `clg` | Console Log | console.log |

## Local Development

Install this as a development extension in Zed:

1. Open the command palette.
2. Run `zed: install dev extension`.
3. Select this repository folder.

Zed snippet extensions use the same JSON snippet format as user snippets. The extension repository needs an `extension.toml` manifest and a `snippets/` directory.

## Publishing

To publish publicly:

1. Push this repository to GitHub.
2. Test it locally as a dev extension.
3. Open a PR to `zed-industries/extensions`.
4. Add this repository as a submodule under `extensions/nextjs-react-ts-js-snippets`.
5. Add an `extensions.toml` entry with version `0.0.1`.
6. Run `pnpm sort-extensions` in the `zed-industries/extensions` repo.

## Attribution

This extension contains snippets created, reviewed, and curated by Vadym Dubykhvist with AI assistance.

The snippets are based on common React, Next.js, TypeScript, TSX, and JSX development patterns. Some command names overlap with existing snippet collections because they are conventional abbreviations in the React and TypeScript ecosystem.

No source extension is intentionally copied wholesale. If any snippet is found to be too close to an existing licensed snippet, please open an issue and it will be rewritten or attributed appropriately.

## License

MIT
