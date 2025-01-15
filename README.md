# How to setup a STM32 project for Align Racing?

1. Download and install [VSCode](https://code.visualstudio.com/)
2. Download and install [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html)
3. Download and install [STM32CubeCLT](https://www.st.com/en/development-tools/stm32cubeclt.html)
5. In VSCode download and install the extension "STM32 VS Code Extension"
6. In the extension tab, launch STM32CubeMX.
7. In STM32CubeMX Create a new project by clicking "Access to MCU Selector"
8. Select the MCU you are going to use, or search for "STM32G431CBT6" if you are only configuring for a test, and click "Start Project".
9. Under the tab "Project Manager", choose a fitting Project name, Project Location and **set the Toolchain / IDE to CMake**.
10. Open the new project folder in VSCode.
11. You can now find the different build commands under the "Run and Debug" tab in VSCode.
12. Try to Build!
