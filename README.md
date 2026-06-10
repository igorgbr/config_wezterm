# Configuração do WezTerm

Este repositório contém a configuração pessoal do WezTerm para o terminal. O arquivo de configuração é escrito em Lua e define algumas opções visuais e de comportamento do terminal.

## Instalação via Flatpak no Linux

1. Instale o Flatpak, se ainda não estiver instalado.
   - Em distribuições baseadas em Debian/Ubuntu: `sudo apt install flatpak`
   - Em Fedora: `sudo dnf install flatpak`
   - Em Arch Linux/Manjaro: `sudo pacman -S flatpak`
2. Adicione o repositório Flathub (se ainda não tiver):
   - `flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo`
3. Instale o WezTerm:
   - `flatpak install flathub org.wezfurlong.wezterm`
4. Execute o WezTerm:
   - `flatpak run org.wezfurlong.wezterm`

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