# unreal-vsvim

Since Unreal Engine does not natively support Neovim, and setting up a stable Neovim environment for Unreal Engine is nearly impossible, I am forced to use Visual Studio for all C++ game development. Fortunately, the VsVIM extension for Visual Studio makes using VS more tolerable, though not nearly as smooth as Neovim. This repository contains my `.vimrc` configurations that override the default VsVIM mappings. These configurations are largely the same as my Neovim setups but are written in Vimscript rather than Lua.

> **Note:** This `.vimrc` configuration file is located in my Windows environment, whereas the Neovim configuration is in my WSL environment. This separation prevents conflicts between the configurations. If both Neovim and Visual Studio are in the same environment and you intend to use these configurations, you may need to perform additional setup to avoid conflicts.
