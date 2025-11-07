## [2.1.0-ncs3-custom-synaptrix-labs] - 2025-11-05

### 🚀 Features

- *(bootloader)* Add LED blink and boot transition after DFU upload

- *(bootloader)* Add DFU timeout and non-blocking CDC-ACM serial recovery


### 🐛 Bug Fixes

- *(bootloader)* Added config for nRF52840 image access hook; ensure nRF5340 board sets SOC_NRF5340_CPUAPP


### 🚜 Refactor

- *(bootloader)* Expose do_boot and add DFU upload callback with reboot


### Chore

- Restore .gitcliff.toml for changelog generation

