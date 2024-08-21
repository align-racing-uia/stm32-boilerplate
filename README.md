# stm32-boilerplate
A boilerplate project for STM32 applications

# How to set up a project like this?

1. Download and install MSYS2 from [here](https://www.msys2.org/) using the windows installer.
2. In the MSYS2 UCRT32 application, run ```pacman -S mingw-w64-ucrt-x86_64-gcc``` and ```pacman -S make```.
3. Download and install VSCode from [here](https://code.visualstudio.com/).
4. Download and install [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html) and [STM32CubeCLT](https://www.st.com/en/development-tools/stm32cubeclt.html).
5. Install the extension named 'STM32 VS Code Extenstion'.
6. If needed, help the extension find the locations of the CubeMX and the CLT.
7. Launch STM32CubeMX, and configure the project to use the microcontroller you need, and hit "Start Project".
8. Under "Project Manager" set a reasonable project name, and project location. The Toolchain / IDE must be CMake.
9. Hit "Generate Code", then use the VSCode extension to "Import CMake Project".