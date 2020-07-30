# Custom Keymap for DZ60RGB ANSI V1 Keyboard
A custom keymap made by Wolvix, for mechanical keyboard DZ60RGB ANSI v1.

This contains the original QMK firmware files for the keyboard, and custom keymap in a separate folder within the keyboard's `keymaps` folder. The custom Keymap and compiled firmware supports [VIA feature](https://caniusevia.com/).

### Usage Guide ###
- To <b>view the keymap layers</b>, take a look at the `layerXX.png` files or `Layout.pdf`
- To <b>edit the keymap using [Online QMK Configurator](https://config.qmk.fm/#/dztech/dz60rgb_ansi/v1/LAYOUT_60_ansi)</b>, use `keymap_qmkconfigurator.json` file. Once done, download the edited keymap and convert to `.c` format using `qmk json2c -o keymap.c /PATH/TO/INPUT/FILE.json` command. Place in `wolvix` keymap folder and compile firmware
- To <b>edit the keymap using VIA Configurator</b>, use `keymap_VIAconfigurator` file in the VIA configurator. There is no need to compile
- To <b>compile without editing</b>, copy `dz60rgb_ansi/keymaps/wolvix` folder to the keyboard's keymap folder in your cloned qmk firmware repo folder before compiling. Example: `qmk_firmware/keyboards/dztech/dz60rgb_ansi/keymaps/`
- To <b>flash pre-compiled firmware</b>, use qmk or qmk toolbox to flash the `dztech_dz60rgb_ansi_v1_wolvix.bin` firmware file

