# setup-riscv-gnu-toolchain

This action sets up a [RISCV GNU toolchain](https://github.com/hydrausb3/riscv-none-elf-gcc-xpack) environment for use in actions.

this branch is hydrausb3 version

ChnMasterOG update

# Usage

Using latest release
```yaml
steps:
- uses: ChnMasterOG/setup-riscv-gnu-toolchain@v5.0
- run: riscv-none-elf-gcc --version
```

Using specific release(used release id which can be find in [RELEASE PAGE](https://api.github.com/repos/hydrausb3/riscv-none-elf-gcc-xpack/releases))
```yaml
steps:
- uses: ChnMasterOG/setup-riscv-gnu-toolchain@v5.0
  with:
    version: 91402143
- run: riscv-none-elf-gcc --version
```

# License

The scripts and documentation in this project are released under the [ISC](COPYING)
