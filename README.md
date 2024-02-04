# setup-riscv-gnu-toolchain

This action sets up a [RISCV GNU toolchain](https://github.com/xpack-dev-tools/riscv-none-elf-gcc-xpack) environment for use in actions.

ChnMasterOG update

# Usage

Using latest release
```yaml
steps:
- uses: ChnMasterOG/setup-riscv-gnu-toolchain@v3.0
- run: riscv-none-elf-gcc --version
```

Using specific release
```yaml
steps:
- uses: ChnMasterOG/setup-riscv-gnu-toolchain@v3.0
  with:
    version: 13.2.0
- run: riscv-none-elf-gcc --version
```

# License

The scripts and documentation in this project are released under the [ISC](COPYING)
