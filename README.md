# Personalização de Terminal

### licença e tecnologias utilizadas
<img src="https://img.shields.io/github/license/henrygoncalvess/Custom_Terminal?style=for-the-badge&labelColor=gray&color=97ca00"> <a href="https://learn.microsoft.com/en-us/powershell/"><img src="https://img.shields.io/badge/powershell-7.5-blue?style=for-the-badge&logo=powershell&logoColor=darkblue&labelColor=gray"></a>

instalação e configuração necessária para personalização de um terminal
  
<details open="open">
<summary>Tabela de Conteúdos</summary>
  
- [Instrução de instalação](#instrução-de-instalação)
  - [Pré-requisitos](#pré-requisitos)
  - [Etapas](#etapas)
- [Instrução de uso](#instrução-de-uso)
- [Exportar uma imagem do tema](#exportar-uma-imagem-do-tema)
- [Configurações do meu tema](#configurações-do-meu-tema)
  
</details>

<br>

## Instrução de instalação

### Pré-requisitos
- **Oh-My-Posh** - [Tutorial de instalação - Windows](https://youtu.be/rHCY562FDVM?si=nqZXS0KNNmJQMe1a)

<br>

### Etapas
**1. para personalizar seu tema, basta abrir o arquivo JSON com o editor de código de sua  
preferência e estilizá-lo da maneira que deseja**

``` bash
# exemplo vscode
code C:\caminho\para\o\tema\meuTema.omp.json

# exemplo notepad
notepad C:\caminho\para\o\tema\meuTema.omp.json
```

<br>

## Instrução de uso
para sempre iniciar o terminal com seu tema, digite o seguinte comando  
no arquivo de configuração do powershell 

`Microsoft.PowerShell_profile.ps1`
``` ps1
oh-my-posh init pwsh --config 'C:\caminho\para\o\tema\meuTema.omp.json' | Invoke-Expression
```

<br>

## Exportar uma imagem do tema
Parâmetro | Descrição
:-- | :--
`--author` | o nome do criador, adicionado depois de "ohmyposh.dev", dentro da imagem
`--background-color` | a cor de fundo hexadecimal a ser usada (por exemplo #222222)
`--output` | nome do arquivo para exportar (por exemplo meu_tema.png)

na linha de comando:

`exemplo`
``` ps1
oh-my-posh config export image --author "seu nome" --background-color 222222 --output meu_tema.png
```

<br>

## Configurações do meu tema
![meu_tema](https://github.com/user-attachments/assets/41104401-9145-456a-832f-dfccd123b8d3)


[ver configurações](custom_theme.omp.json)
