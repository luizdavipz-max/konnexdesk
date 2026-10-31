# KonnexDesk

Programa de suporte remoto usado pela equipe do [Konnex](https://konnexgestao.com.br).

É uma versão modificada do [RustDesk](https://github.com/rustdesk/rustdesk) 1.5.0, distribuída sob a mesma licença, a [GNU AGPL-3.0](LICENCE). Todo o código do programa está neste repositório.

## O que mudou em relação ao RustDesk

- nome, ícones, logo e cores;
- servidor próprio e chave pública do servidor;
- chave que confere a configuração assinada (`konnex/custom-*.txt`);
- duas versões: `KonnexDesk.exe` para o cliente, que só recebe conexão, e `KonnexDesk-Suporte.exe` para a equipe;
- links do programa e aviso de licença na tela Sobre;
- só a compilação para Windows x64 (`.github/workflows/konnexdesk-windows.yml`).

RustDesk é marca de seus respectivos donos. Este projeto não tem vínculo com a equipe do RustDesk.
