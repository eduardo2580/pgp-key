# PGP Key — Eduardo Souza Rodrigues

My public PGP key, for encrypting messages to me or verifying my signatures.

## Key details

| | |
|---|---|
| **Name** | Eduardo Souza Rodrigues |
| **Key ID** | `0x67D64937065DCA8B` |
| **Fingerprint** | `4153 DB98 EF02 8C23 9889  46B5 67D6 4937 065D CA8B` |
| **Algorithm** | Ed25519 (sign) / Curve25519 (encrypt) |
| **Created** | 2026-07-07 |
| **Expires** | 2028-07-07 |

> Always verify the fingerprint against another channel (in person, a signed message, a profile bio, etc.) before trusting this key.

## Importing the key

Clone this repo, then import the key with GPG:

```bash
gpg --import Eduardo_Souza_Rodrigues_0x67D64937065DCA8B_public.asc
```

Or, if you fetched it from a keyserver:

```bash
gpg --keyserver hkps://keys.openpgp.org --recv-keys 0x67D64937065DCA8B
```

## Verifying the fingerprint

After importing, confirm the fingerprint matches the one listed above:

```bash
gpg --fingerprint 0x67D64937065DCA8B
```

## Sending me an encrypted message

```bash
gpg --encrypt --armor --recipient 0x67D64937065DCA8B message.txt
```

This produces `message.txt.asc`, which only I can decrypt.

## Verifying my signature

If I've signed something, verify it with:

```bash
gpg --verify signature.asc file
```

## License

The key material in this repository is public by design and free to use for the purposes above.
