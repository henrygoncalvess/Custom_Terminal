# Personalização de Terminal

> Configurações do meu tema

![my theme config](/my-theme-photo.png)

## 📋 Conteúdo

- [Visão Geral](#Overview)
- [Instrução de instalação](#installation)
  - [Pré-requisitos](#pré-requisitos)
  - [Etapas](#etapas)
- [Instrução de uso](#use)
- [Exportar uma imagem do tema](#export-image)
- [Configurações do meu tema](#theme-config)
  
<br>

<a name="Overview"></a>
## 🔍 Visão Geral

Instalação e configurações necessárias para a exportação, importação e personalização de um terminal.

<br>

<a name="installation"></a>
## ⚙️ Instrução de instalação

### Pré-requisitos
**Oh-My-Posh**  
🎥 [Tutorial de instalação - Windows](https://youtu.be/rHCY562FDVM?si=nqZXS0KNNmJQMe1a)  
📄 [Tutorial de instalação - Linux](https://ohmyposh.dev/docs/installation/linux)

<br>

### Etapas
para personalizar seu tema, basta importar o arquivo JSON dele, enviar para algum  
diretório e com o editor de código de sua preferência estilizá-lo da maneira que deseja

`Para exportar o arquivo do tema para um diretório:`
``` bash
# linux
oh-my-posh config export --output ~/caminho/para/o/tema/meu-tema.omp.json

#windows
oh-my-posh config export --output C:\caminho\para\o\tema\meu-tema.omp.json
```

`Para editar o arquivo: (com vscode)`
```bash
# Linux
code ~/caminho/para/o/tema/meu-tema.omp.json

# Windows
code C:\caminho\para\o\tema\meu-tema.omp.json
```

<br>

<a name="use"></a>
## 📜 Instrução de uso

### Linux

para iniciar o terminal com seu tema todas as vezes, digite o seguinte comando  
no arquivo de configuração do perfil

**Pode ser:** `~/.bashrc` `~/.profile` ou `~/.bash_profile`
``` bashrc
eval "$(oh-my-posh init bash --config ~/caminho/para/o/tema/meu-tema.omp.json)"
```

### Windows

para iniciar o terminal com seu tema todas as vezes, digite o seguinte comando  
no arquivo de configuração do powershell 

`C:\Users\Usuario\Documents\Powershell\Microsoft.PowerShell_profile.ps1`
``` ps1
oh-my-posh init pwsh --config 'C:\caminho\para\o\tema\meu-tema.omp.json' | Invoke-Expression
```

<br>

<a name="export-image"></a>
## 📷 Exportar uma imagem do tema
Parâmetro | Descrição
:-- | :--
`--author` | o nome do criador, aparece depois de "ohmyposh.dev", dentro da imagem
`--background-color` | a cor de fundo hexadecimal a ser usada (_por exemplo #222222_)
`--output` | nome do arquivo para exportar (_por exemplo meu_tema.png_)

na linha de comando:

`exemplo`
``` ps1
oh-my-posh config export image --author "seu nome" --background-color 222222 --output meu_tema.png
```

<br>

<a name="theme-config"></a>
## ⚙️ Configurações do meu tema

([**clique aqui**](my-theme.omp.json)) para acessar as configurações do tema

<br>

<a name="license"></a>
## 📄 Licença

Este projeto está licenciado sob a [MIT License](https://github.com/henrygoncalvess/AI-photos-community/blob/main/LICENSE).

---

<div align="center">
  <p>Feito com ❤️ por <a href="https://github.com/henrygoncalvess">Henry Gonçalves</a></p>
  <p>Deixe uma ⭐ no repositório se ele for útil para você!</p>
</div>
