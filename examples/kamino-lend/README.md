# kamino-lend

Autogenerated CPI client for the Kamino Lend program.

CPI helpers for the [Kamino Lend](https://github.com/Kamino-Finance/klend) program.

This crate was automatically generated by
[anchor-gen](https://github.com/saber-hq/anchor-gen), a crate for generating
Anchor CPI helpers from JSON IDLs.

License: Apache-2.0

WARNING: the `refresh_reserves_batch` instruction is not included in the IDL because it has no accounts, breaking Anchor codegen.

```json
    {
      "name": "refresh_reserves_batch",
      "discriminator": [144, 110, 26, 103, 162, 204, 252, 147],
      "accounts": [],
      "args": [
        {
          "name": "skip_price_updates",
          "type": "bool"
        }
      ]
    },
```
