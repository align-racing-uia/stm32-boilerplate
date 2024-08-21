# stm32-boilerplate
A boilerplate project for STM32 applications

# How to set up a project like this?

1. Download and install MSYS2 from [here](https://www.msys2.org/) using the windows installer.
2. In the MSYS2 UCRT32 application, run ```pacman -S mingw-w64-ucrt-x86_64-gcc``` and ```pacman -S make```.
3. Add ```C:/msys64/usr/bin``` and ```C:/msys64/ucrt64/bin``` to the PATH ([Guide here](https://www.architectryan.com/2018/03/17/add-to-the-path-on-windows-10/))
4. Download and install VSCode from [here](https://code.visualstudio.com/).
5. Install the extension named 'STM32 VS Code Extenstion' in VSCode (You can find VSCode extenstions in the left toolbar, with 4 blocks as a symbol).
6. Download and install [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html) and [STM32CubeCLT](https://www.st.com/en/development-tools/stm32cubeclt.html).
7. If needed, help the extension find the locations of the CubeMX and the CLT.
8. Launch STM32CubeMX, and configure the project to use the microcontroller you need (Use e.g. stm32g431cbt6 for testing), and hit "Start Project".
9. Under "Project Manager" set a reasonable project name, and a project location you want to have the project in. The Toolchain / IDE must be CMake.
10. Hit "Generate Code", then use the VSCode extension (A butterfly icon on the left bar) to "Import CMake Project".
11. Try to Build the project, by using the toolbar on the bottom of VSCode.