# STM32F3Discovery board support for Mbed OS 6

Since Mbed OS 6 [STM32F3Discovery](https://www.st.com/en/evaluation-tools/stm32f3discovery.html) support has been dropped from Mbed OS repository.
This project returns support of this board as custom one.

## License

Unless specifically indicated otherwise in a file, files are licensed under the MIT license.

## Usage

1. Add this repository to your project as library:

   ```
   mbed add https://github.com/vznncv/TARGET_DISCO_F303VC
   ```
   
2. Copy `custom_targets.json` to your project root:

   ```
   cp TARGET_DISCO_F303VC/custom_targets.json custom_targets.json
   ```
