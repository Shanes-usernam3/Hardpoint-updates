# HardPoint Hypervisor updates

Signed Debian package archive for [HardPoint Hypervisor](https://shanes-usernam3.github.io/hardpoint-updates/).
Published automatically by the HardPoint build pipeline; do not edit by hand.

- `stable`: releases
- `testing`: test builds (also follows stable)

Servers pick this up on their own (Settings → Updates). Every download is
verified by apt against the archive signing key shipped with HardPoint:

```
HardPoint Hypervisor Archive Signing Key <noreply@hardpoint.invalid>
65A3 393C 7A94 011D C062  5B4C 072C 3C46 C7A3 BADA
```

The public key is also here: [hardpoint-archive-keyring.asc](hardpoint-archive-keyring.asc).
