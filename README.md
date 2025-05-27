ERC20 and ERC721 demos written in Fe language.

Showcases modular and reusable components with type interfaces that are able to express different target sytems even outside EVM.

## Building

```
fe check <PATH TO INGOT>
# for example
fe check ingots/ERC20
fe check ingots/ERC721
```

## Printing ingot resolver tree

```
fe tree <PATH TO INGOT>
# for example
fe tree ingots/ERC20
```

Example output:

```
$ fe tree ingots/ERC20
ERC20 v0.0.1
├── map v0.0.1
│   └── std v0.0.1
├── solidity v0.0.1
│   ├── map v0.0.1
│   │   └── std v0.0.1
│   ├── evm v0.0.1
│   │   └── std v0.0.1
│   └── std v0.0.1
└── std v0.0.1
```

## License

MIT
