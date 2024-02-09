## eevm_abi

eevm_abi is a erlang library for encoding and decoding EVM ABI format.
It's does not support fixed,ufixed types yet.

By default eevm_abi for keccak256 calculation uses library esha3 it's slow,
but pure erlang implementation, in production it's recommended to add ksha3
to your project, eevm_abi will detect presence of ksha3 and will use it.

```
{ksha3, {git, "https://github.com/onyxrev/ksha3", "master"}}
```

### how to use



