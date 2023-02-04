## RTT CI QEMU

some CI suite of RTT in QEMU

### docs

tech docs

#### steps

ONLY check 'main' branch

1. pull main branch
2. modify .config to combine bsp & package
3. build via `scons`
4. sp: start program via QEMU

### reference

1. https://github.com/RT-Thread/rt-thread/issues/6458
2. https://github.com/RT-Thread/pkgs-test
