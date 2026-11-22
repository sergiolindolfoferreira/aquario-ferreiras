# Aquário Ferreira’s 🐠

Aplicação web para gerir vários aquários da família Ferreira.

## Funcionalidades
- Dashboard individual por aquário
- Gestão de múltiplos aquários
- Agenda e conclusão de tarefas
- Histórico de medições pH, KH, GH, NO₂ e temperatura
- Catálogo de espécies e equipamentos
- Exportação e importação de cópias de segurança JSON
- Interface adaptada ao iPad, iPhone e computador

## Dados
Esta primeira versão utiliza **localStorage**. Os dados não são sincronizados entre dispositivos e podem perder-se se o navegador eliminar o armazenamento. Faz backups regulares em **Dados → Descarregar JSON**. Não existe backend nem autenticação.

## Publicação via GitHub Pages
1. Acede às definições do repositório (Settings → Pages).
2. Em **Build and deployment**, escolhe **Deploy from a branch**.
3. Escolhe o ramo **main** e a pasta **/(root)** e guarda.
4. Quando o GitHub Pages indicar que a publicação terminou, abre:
   https://sergiolindolfoferreira.github.io/aquario-ferreiras/

A publicação só fica acessível depois de ativada e concluída no GitHub.

## Desenvolvimento
Todo o front-end está em `index.html`, sem dependências externas. O repositório é público: não coloques senhas, dados sensíveis nem informação privada no código.

## Nota de aquariofilia
Os valores da água são apenas registos, não diagnósticos. Se houver NO₂ detetável ou sinais de sofrimento dos peixes, confirmar o teste e atuar de acordo com orientação adequada. O Sera Aqua-Test Set existente não mede amónia.
