# nvim-sfc

This is my single file Neovim configuration which consists of ~10 plugins in total, including LSP support in uder 100 lines of code.

If you want to learn more about the philosophy behind this setup, you can check out [this post](https://jacksmith.xyz/blog/neovim-configuration-one-file-to-rule-them-all/) on it. 

**Using This Configuration**

1. Clone the repo, and `mv` the `init.lua` file into your `~/.config/nvim` directory.
2. Open Neovim
3. Run `:Lazy`, and install/update the packages if needed
4. Run `:Mason` and install any language servers you need
5. Add the language servers to your `init.lua` file, e.g. `require("lspconfig").lua_ls.setup{}`, replacing `lua_ls` with the language server you have installed

Now use Neovim!
