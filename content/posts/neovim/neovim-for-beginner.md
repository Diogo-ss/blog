+++
title = 'Neovim for Beginner'
date = 2024-04-22T11:05:15-03:00
draft = false
description = "A simple config in Lua for beginners."
summary = "A simple config in Lua for beginners.."
tags = ["neovim", "nvim", "lua"]
ShowToc = true
TocOpen = true
+++

## Intrudução

Configurar o Neovim do zero pode ser um pouco desafiador de início,
além disso é um editor com uma longa curva de aprendizado, mas com a prática de uso,
o editor se mostra extremamente produtivo.

## Gerenciador de pacote

Neste tutorial usaremos o [Lazy.nvim](https://github.com/folke/lazy.nvim), por ser extensivo e fácil de configurar.
Premerio acesse o direotório de configuração.

```sh
# cria pasta de congiração caso não exista.
mkdir -p ~/.config/nvim

# altera o direotório.
cd ~/.config/nvim
```

Crie um arquivo `init.lua`, esse arqivo é carregado de forma automática pelo editor.

```sh
touch init.lua
```
