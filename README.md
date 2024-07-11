# Configuración básica Nvim

### 📁 Base

Es la carpeta donde se configura el core de nvim, como lazy-vim y los mappings básicos.

### 📁 Configs

En esta carpeta van las configuraciones de los plugins, como lazy, lsp, mason, etc.

## 🚧 Requisitos

Nvim [0.9.5](https://github.com/neovim/neovim/releases/tag/v0.9.5)

[Ripgrep](https://github.com/BurntSushi/ripgrep) opcional

[Node](https://nodejs.org/en/download) version 18 o superios. Esto es para algunos LSP.

## 🖥 Installation

### Linux:

Borrar configuracion anterior de nvim en caso de que exista:

```
rm -rf ~/.config/nvim

rm -rf ~/.local/share/nvim
```

Luego clonar el repositorio:

```
git clone https://github.com/javikuma/nvim-config.git ~/.config/nvim && nvim
```

### Windows:

```
rm -Force ~\AppData\Local\nvim
rm -Force ~\AppData\Local\nvim-data
```

```
git clone https://github.com/javikuma/nvim-config.git $ENV:USERPROFILE\AppData\Local\nvim && nvim
```

Una vez instalado los plugins ejecutar `:MasonInstallAll`.
