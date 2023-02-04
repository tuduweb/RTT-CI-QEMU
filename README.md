## RTT CI QEMU

some CI suite of RTT in QEMU

### docs

tech docs

#### main steps

ONLY check 'main' branch

1. pull main branch
2. modify .config to combine bsp & package
3. build via `scons`
4. sp: start program via QEMU

#### package checker action

a action of Action CI, to check compatibility of the package and RTT(master or other).

1. `action/checkout@v3`
2. pull/checkout action repo. (or docker?)
3. check
4. output (visualization)

### reference

1. https://github.com/RT-Thread/rt-thread/issues/6458
2. https://github.com/RT-Thread/pkgs-test
