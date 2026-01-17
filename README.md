# Qualcomm Products Board Support Package (BSP) HLOS Sync scripts

## Why was these scripts created?
1. These scripts was created to automate the process of syncing the Qualcomm Products Board Support Package (BSP) sources.
2. Qualcomm had released the "Release Note" for every Software Product (SP), but sometimes it's hard to find the correct sources or hard to use for the SP.
3. These scripts helps to sync the Qualcomm Products BSP sources easily.

## How to use?
1. Clone this repository
2. Run the scripts with the following command
3. Copy or Unzip the BSP packages to the same directory where the scripts are located.
4. Modify the "build.sh" script to set the correct paths if needed.
5. Run the build script:
   ```bash
   bash build.sh
   ```
6. The scripts will automatically sync the BSP sources and prepare the build environment.

## Reference
- [SM8550 BSP Compile Guide](https://hackmd.io/@EdwardWu/Kalama_BSP_CompileGuide)

## License
These scripts is licensed under the GPL-3.0 License. See the [LICENSE](LICENSE) file for details.

## Credits
- [Qualcomm Technologies, Inc.](https://www.qualcomm.com/)
- [Qualcomm Chipcode](https://chipcode.qti.qualcomm.com)
- [CodeLinaro](https://git.codelinaro.org/)
- [Jyotiraditya](https://github.com/imjyotiraditya)
- [EdwardWu](https://github.com/bluehomewu)
- [LittlenineEnnea](https://github.com/LittlenineEnnea)
- [QRD-Development](https://github.com/QRD-Development)
