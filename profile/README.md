<p align="center">
  <img src="https://raw.githubusercontent.com/refrax-xyz/.github/main/profile/header.png" alt="Refrax — one file in, sixteen facets out" width="100%">
</p>

<p align="center">
  <b>Object storage, coordinated on Solana.</b><br>
  Every file becomes 16 facets on 16 independent nodes. Any 5 bring it back.<br>
  Solana keeps the receipt, never the bytes.
</p>

<p align="center">
  <a href="https://refrax.xyz">refrax.xyz</a> ·
  <a href="https://x.com/refrax_xyz">@refrax_xyz</a> ·
  <a href="https://github.com/refrax-xyz/refrax-node">refrax-node</a> ·
  <a href="https://github.com/refrax-xyz/refrax-node/blob/main/docs/protocol.md">protocol</a>
</p>

### Run a node

```sh
curl -fsSL https://raw.githubusercontent.com/refrax-xyz/refrax-node/main/install.sh | sh
refrax devnet up        # a registry and 16 nodes on your machine
```

| Repository | What it is |
|---|---|
| [**refrax-node**](https://github.com/refrax-xyz/refrax-node) | The storage node in Rust: Reed–Solomon 16/5, merkle commitments, proofs of storage, slashing, CLI and a local devnet. Apache-2.0. |

**Status:** devnet preview, not audited. Security reports: see [SECURITY.md](https://github.com/refrax-xyz/refrax-node/blob/main/SECURITY.md).
