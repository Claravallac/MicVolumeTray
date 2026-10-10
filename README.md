# Mic Volume Tray

🇧🇷 Português · [🇺🇸 English](#english)

Controle o **volume e o mudo do microfone** direto da bandeja do Windows. Um ícone pequeno mostra o nível em tempo real, e um clique abre um painel no estilo Windows 11 para ajustar tudo sem abrir as configurações de som.

## Recursos

- **Ícone vivo na bandeja:** mostra o volume e uma barra com o nível do microfone (7 estilos à escolha).
- **Painel rápido:** clique no ícone para ajustar o volume e trocar de microfone.
- **Mudo em um toque:** clique do meio no ícone, tecla `M` no painel ou **atalho global** (Ctrl+Alt+M, Ctrl+Shift+M ou Ctrl+Alt+Espaço), mesmo com outro programa em primeiro plano.
- **Roda do mouse:** role sobre o ícone para mudar o volume, com passo de 1%, 2%, 5% ou 10%.
- **Fixar volume:** impede que o Windows ou outros programas mexam no volume do microfone.
- **Ouvir meu microfone:** teste de áudio ao vivo (use fones para evitar eco).
- **Aviso de estouro:** o medidor fica vermelho quando o som está alto demais.
- **Som ao silenciar/reativar:** pode ser desligado.
- **Tema:** automático (segue o Windows), claro ou escuro, com a cor de destaque do sistema.
- **Idioma:** Português e English, automático ou manual.
- **Atalhos de ajuda:** dispositivos de gravação e privacidade do microfone do Windows.
- **Atualização automática:** confere as releases do GitHub ao abrir e a cada 4 horas.
- **Leve:** um único `.exe`, sem dependências, sem serviço em segundo plano.

## Instalação

1. Baixe o instalador mais recente em [**Releases**](https://github.com/Claravallac/MicVolumeTray/releases).
2. Execute `MicVolumeTray_Setup_vX.Y.Z.exe` (não precisa de administrador).
3. Marque se quer iniciar com o Windows e conclua.

O ícone aparece na bandeja. Se o Windows o esconder no menu `^`, ative **Manter ícone sempre visível** nas Preferências.

## Como usar

| Ação | Resultado |
|---|---|
| Clique no ícone | Abre o painel de volume |
| Clique do meio no ícone | Silencia / reativa |
| Roda do mouse sobre o ícone | Ajusta o volume |
| Clique direito no ícone | Menu: trocar microfone, configurações, sobre, sair |
| Atalho global (opcional) | Silencia / reativa |

Fechar a janela de configurações **não** encerra o programa; ele continua na bandeja. Para sair, use **Sair** no menu do ícone.

## Linha de comando

| Opção | Efeito |
|---|---|
| `--hidden` | Inicia só na bandeja |
| `--show` | Abre a janela mesmo com "iniciar minimizado" |
| `--no-meter` | Desliga o medidor |
| `--no-middle-click` | Desliga o mudo no clique do meio |
| `--no-wheel` | Desliga o volume pela roda do mouse |
| `--pin-tray` | Mantém o ícone sempre visível |
| `--interval=100` | Intervalo de atualização em ms (20–500) |

As preferências ficam em `HKEY_CURRENT_USER\Software\MicVolumeTray`.

---

<a id="english"></a>

# Mic Volume Tray (English)

Control your **microphone volume and mute** right from the Windows tray. A small icon shows the live input level, and one click opens a Windows 11-style panel, so you don't have to dig through Sound settings.

## Features

- **Live tray icon** with volume and an input level bar (7 styles).
- **Quick panel:** click the icon to set the volume and switch microphones.
- **One-touch mute:** middle-click the icon, press `M` in the panel, or use a **global hotkey** (Ctrl+Alt+M, Ctrl+Shift+M or Ctrl+Alt+Space) from any app.
- **Mouse wheel** over the icon changes the volume in 1%, 2%, 5% or 10% steps.
- **Lock volume:** stops Windows or other apps from changing the mic level.
- **Listen to my microphone:** live monitoring (use headphones to avoid echo).
- **Clipping warning** when the signal is too loud.
- **Mute sound** (optional), **light/dark/auto theme**, **Portuguese/English UI**.
- **Help shortcuts** to Windows recording devices and microphone privacy.
- **Auto-update** from GitHub Releases (on launch and every 4 hours).
- **Tiny:** a single `.exe`, no dependencies.

## Install

Download the latest installer from [**Releases**](https://github.com/Claravallac/MicVolumeTray/releases) and run it (no admin rights needed).

## Usage

Click the icon for the volume panel, middle-click to mute, scroll over it to change volume, right-click for the menu. Closing the settings window keeps the app running in the tray; use **Exit** in the tray menu to quit.

Command-line options: `--hidden`, `--show`, `--no-meter`, `--no-middle-click`, `--no-wheel`, `--pin-tray`, `--interval=100`.
