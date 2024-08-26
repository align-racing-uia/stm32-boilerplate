# How to setup a STM32 project for Align Racing?

1. Download and install [VSCode](https://code.visualstudio.com/)
2. Download and install [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html)
3. In VSCode download and install the extension "STM32 for VSCode"
4. In STM32CubeMX Create a new project by clicking "Access to MCU Selector"
5. Select the MCU you are going to use, or search for "STM32G491CET6" if you are only configuring your computer, and click "Start Project".
6. Under the tab "Project Manager", choose a fitting Project name, Project Location and *set the Toolchain / IDE to Makefile*.
7. Open the new project folder in VSCode, open "STM32 for VSCode" in the sidebar of VSCode.
8. Click "Install Build Tools", and wait for the process to finish.
9. Try to Build!
