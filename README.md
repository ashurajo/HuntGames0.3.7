# HuntGames

HuntGames is an Android memory editor and analysis on ARM64 devices. This project uses the kernel for Read and Write memory

## Requirements

- Android 10+
- ARM64 device
- Root access
- Unlocked bootloader
- Kernel configs: CONFIG_KALLSYMS=y and CONFIG_KALLSYMS_ALL=y

## Installation

### Patching Boot
#### Compatible with any root method

1. Download apk in the releases section.
2. Open HuntGames, go to Patch Boot tab (recommended to set key in home/settings tab)
3. click on select boot img, select file and start patching.
4. flash the "patched_boot.img" of your downloads folder (If it doesn't exist, check the installation logs and check if your kernel is compatible.)
5. reboot and enjoy.

### Using APatch KPM

1. Download apk and kpm in the releases section.
2. load kpm in APatch (It is recommended to configure your key in the APatch app kpm control, just enter your key as argument.)
3. Open HuntGames (If you configured your key in kpm control, configure the same key in HuntGames)
4. start and enjoy.

## Community and Support

For discussions and support, join our Telegram group: [HuntGames Telegram Group](https://t.me/huntgames7).

## Contributing

We welcome contributions! Please fork the repository, create a feature branch, and submit a pull request. Ensure your code adheres to the project's coding standards and passes all tests.

## Credits for patch in kernel and kpm

[bmax121](https://github.com/bmax121)
[KernelPatch](https://github.com/bmax121/KernelPatch) and its contributors

---

*Note: The project is in its early stages. Please report any issues or bugs in the Issues section.*
