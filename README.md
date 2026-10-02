# Youtube Downloader & Voice Remover · Instaladores

Este repositório existe **só pra hospedar os instaladores** do Youtube Downloader & Voice Remover.
Ele é público pra que o app consiga conferir e baixar as atualizações sozinho. **O código-fonte não está aqui.**

## Baixar

Pegue a versão mais recente em **[Releases](../../releases/latest)**:

| Sistema | Arquivo |
|---|---|
| macOS · Apple Silicon (M1, M2, M3, M4) | `Youtube-Downloader-Voice-Remover-<versão>-Mac-AppleSilicon.dmg` |
| Windows 10 e 11 | `Youtube-Downloader-Voice-Remover-<versão>-Windows-Instalador.exe` |

O arquivo `.tar.xz` e o `latest.json` são usados pelo próprio app na atualização automática. Não precisa baixar.

### macOS: a primeira abertura é bloqueada

O app não tem a assinatura paga da Apple, então o macOS bloqueia a primeira abertura. O app não está danificado.

1. Abra o DMG e arraste o app pra pasta **Aplicativos**.
2. Dê dois cliques no app. Quando aparecer o bloqueio, clique em **Cancelar**.
3. Abra **Ajustes do Sistema > Privacidade e Segurança**, role até o fim e clique em **Abrir Mesmo Assim**.
4. Confirme. Nas próximas vezes abre normal.

### Windows: aviso azul do SmartScreen

Clique em **Mais informações** e depois em **Executar assim mesmo**.

## Atualizações

A partir da versão 1.1.0 o app se atualiza sozinho, no Mac e no Windows:

- confere se tem versão nova ao abrir e a cada 4 horas;
- baixa em segundo plano e confere se o arquivo chegou inteiro;
- avisa com a faixa **"Tem uma versão nova"**. Dá pra clicar em **Atualizar e reiniciar** na hora, ou deixar: a versão nova entra quando o app for fechado.

No Mac, a atualização automática funciona com o app dentro da pasta Aplicativos (ou de outra pasta comum). Aberto direto do DMG, ele só avisa.
