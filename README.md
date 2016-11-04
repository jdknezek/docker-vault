This is an automated build for [jcoglan/vault](https://github.com/jcoglan/vault).

You'll need to provide one of the following environment variables:
* `-e VAULT_KEY=key`
* `-e USER` (provides the exported `$USER` on Linux)
* `-e USERNAME` (provides `%USERNAME%` on Windows)

If you'd like to use Vault's `--config` mode to store settings, you'll want to provide a volume for `/root/.vault`.
