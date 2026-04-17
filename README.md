# AstroNvim Template

## Changes to AstroNvim Template from Russ

1. [Add in LSPs for Typescript, Prettier, and ESLint](https://github.com/russellmacshane/astronvim-template-v6/commit/1729269355ce166d92a3d253c17c28a92b115be6)
2. [Fix issue with wallaby that has a deno file where the LSP doesn't work right](https://github.com/russellmacshane/astronvim-template-v6/commit/235056bbce799278d7426826282ef18eae991a85)
3. [Turn off relative numbers](https://github.com/russellmacshane/astronvim-template-v6/commit/2b563672b292c438452e2fe53e92e3c24c65f881)
4. [Copy Diagnostic Line to Clipboard](https://github.com/russellmacshane/astronvim-template-v6/commit/7747493fa7992e2592fbe86068d7dd85dcf666ef)
5. [Copy Relative Path](https://github.com/russellmacshane/astronvim-template-v6/commit/51f338ade2bc91cf545ab436cea920b2bab4844d)
6. [Customize the Opening Dashboard](https://github.com/russellmacshane/astronvim-template-v6/commit/3b342a09c08902c5cec37312aa39bb62606c599f)
7. [grr uses snack picker instead of default diagnostic window](https://github.com/russellmacshane/astronvim-template-v6/commit/8cda571a7c6a7ca0b529275905904903665f2bc3)
8. [Use Tokyonight Color Scheme](https://github.com/russellmacshane/astronvim-template-v6/commit/2b793815473171c5da2c56a8c7f0cedb746e423a)
9. [Install Tailwind Community Pack](https://github.com/russellmacshane/astronvim-template-v6/commit/2bf1a3c187db56d219a798f748916a3ae0928266)
10. [Fix Prettier Issues](https://github.com/russellmacshane/astronvim-template-v6/commit/3e9a19d8ff032c9477238907d168d19f491a496b)

---

**NOTE:** This is for AstroNvim v6+

A template for getting started with [AstroNvim](https://github.com/AstroNvim/AstroNvim)

## 🛠️ Installation

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak
```

#### Create a new user repository from this template

Press the "Use this template" button above to create a new repository to store your user configuration.

You can also just clone this repository directly if you do not want to track your user configuration in GitHub.

#### Clone the repository

```shell
git clone https://github.com/<your_user>/<your_repository> ~/.config/nvim
```

#### Start Neovim

```shell
nvim
```
