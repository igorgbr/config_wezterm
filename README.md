# Configuração do WezTerm

Este repositório contém a configuração pessoal do WezTerm para o terminal. O arquivo de configuração é escrito em Lua e define algumas opções visuais e de comportamento do terminal.

## O que este arquivo faz

A configuração em `.wezterm.lua` define:

- `color_scheme = 'Red Alert (Gogh)'`
  - Define o esquema de cores usado pelo terminal.
- `font_size = 14`
  - Ajusta o tamanho da fonte para 14 pontos.
- `enable_tab_bar = true`
  - Habilita a barra de abas para visualizar e alternar entre múltiplas guias.
- `window_background_opacity = 0.44`
  - Define a opacidade do fundo da janela em 44%.

## Como usar

Coloque o arquivo `.wezterm.lua` na pasta de configuração do WezTerm (normalmente `~/.config/wezterm/`) e reinicie o WezTerm para aplicar as alterações.