# tree-sitter-flang

Tree-sitter grammar for the [FLang](https://github.com/shadept/flang) programming language.

## Installation

```bash
npm install tree-sitter-flang
```

## Usage

### Generate the parser

```bash
npx tree-sitter generate
```

### Build

```bash
npx tree-sitter generate && npx tree-sitter build
```

### Test

```bash
npx tree-sitter test
```

### Playground

```bash
npx tree-sitter build --wasm && npx tree-sitter playground
```

## License

MIT
