# ssh

Scripts and configuration for working with SSH keys and the SSH client.

| File | Description |
|------|-------------|
| `0-use_a_private_key` | Connects to the server as `ubuntu` using the private key `~/.ssh/school` |
| `1-create_ssh_key_pair` | Creates a 4096-bit RSA key pair named `school`, protected by the passphrase `betty` |
| `2-ssh_config` | SSH client configuration: uses `~/.ssh/school` and refuses password authentication |

## Usage

```
./0-use_a_private_key
./1-create_ssh_key_pair
```

`2-ssh_config` is meant to be added to `~/.ssh/config`.
