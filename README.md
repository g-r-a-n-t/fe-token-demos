ERC20 and ERC721 demos written in Fe language.

These demos are kept in sync with the local `fe` checkout’s `core`/`std` ingots
via `ingots/core/src` and `ingots/std/src` symlinks (pointing at
`~/workshop/fe/ingots/`).

## Building

```bash
fe check
# or:
fe check ingots/ERC20
fe check ingots/ERC721
```

## Printing ingot resolver tree

```bash
fe tree ingots/ERC20
fe tree ingots/ERC721
```

Example output:

```bash
$ fe tree ingots/ERC20
ERC20 v0.0.1
├── std v0.1.0
│   └── core v0.1.0
└── core v0.1.0
```

## License

MIT
