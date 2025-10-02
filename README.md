# Tag Team Dub Files

Este repositório contém os arquivos de dublagem gerenciados pelo Tag Team Studio Sparking Launcher.

## Estrutura do Repositório

- `/manifest.json` - Arquivo de controle de versões e metadados dos arquivos
- `/files/characters` - Diretório contendo os arquivos de dublagem

## Manifest.json

O arquivo `manifest.json` contém:
- Versão atual do manifest
- Data da última atualização
- Lista de arquivos disponíveis com:
  - Nome do arquivo
  - Versão
  - Tamanho em bytes
  - Checksum SHA-256
  - URL de download
  - Status do arquivo

## Como Atualizar

1. Adicione os novos arquivos de dublagem no diretório `/files/characters/`
2. Atualize o `manifest.json` com as informações dos novos arquivos
3. Faça commit ou push das alterações
4. O launcher detectará automaticamente as atualizações na próxima verificação 
