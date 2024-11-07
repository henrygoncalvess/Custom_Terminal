# Personalização de Terminal

### licença e tecnologias utilizadas
<img src="https://img.shields.io/github/license/henrygoncalvess/Custom_Terminal?style=for-the-badge&labelColor=gray&color=97ca00"> <a href="https://learn.microsoft.com/en-us/powershell/"><img src="https://img.shields.io/badge/powershell-7.5-blue?style=for-the-badge&logo=powershell&logoColor=darkblue&labelColor=gray"></a>

configurações necessárias para personalização de um terminal
  
<details open="open">
<summary>Tabela de Conteúdos</summary>
  
- [Instrução de instalação](#instrução-de-instalação)
  - [Pré-requisitos](#pré-requisitos)
  - [Etapas](#etapas)
- [Instrução de uso](#instrução-de-uso)
  
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
para iniciar automaticamente o terminal com seu tema, digite o seguinte comando  
no arquivo de configuração do powershell 

`Microsoft.PowerShell_profile.ps1`
``` ps1
oh-my-posh init pwsh --config 'C:\caminho\para\o\tema\meuTema.omp.json' | Invoke-Expression
```
