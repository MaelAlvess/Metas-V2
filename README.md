# WealthPath 2.0 — PWA para iPhone

## O que contém
Dashboard dark premium, cartões ilustrados de quatro metas, aportes e retiradas, edição e criação de metas, comparação de prazos, simulação de juros compostos, histórico, backup JSON e lembrete mensal em arquivo ICS. Inclui ícones, manifesto PWA e service worker offline. As imagens de carro e casa são **ilustrações vetoriais locais**, não fotografias reais.

## Dados iniciais
Reserva R$ 1.279 de R$ 18.000; Jetta R$ 80.000; entrada/custos da casa R$ 250.000; liberdade financeira R$ 900.000 (meta editável); orçamento mensal R$ 500; despesas essenciais R$ 3.000. A divisão inicial é R$ 400 reserva e R$ 100 casa, editável.

## Publicação pelo iPhone, sem notebook
1. No app Arquivos do iPhone, descompacte o ZIP.
2. No Safari, entre em github.com e crie um repositório público (sem dados pessoais).
3. Envie **o conteúdo da pasta** `wealthpath-pwa` à raiz do repositório (incluindo `assets` e `icons`); na interface móvel do GitHub, talvez seja necessário solicitar a versão para computador.
4. Em Settings > Pages, escolha Deploy from a branch, `main`, `/ (root)` e salve.
5. Espere o GitHub Pages fornecer a URL HTTPS; abra no Safari, toque em Compartilhar > Adicionar à Tela de Início > Adicionar.
6. Faça um aporte de teste e exporte um backup JSON em Ajustes.

**Importante:** abrir o `index.html` diretamente pelo app Arquivos não instala o PWA; é preciso publicar em HTTPS. GitHub Pages hospeda os arquivos estáticos, mas não sincroniza os registros. Dados financeiros são armazenados localmente no navegador (localStorage), não no GitHub. Se apagar os dados do Safari, pode perdê-los. Faça backups frequentes. Não há widgets nativos, login, conexão bancária, sincronização ou notificações push. Os retornos financeiros são hipotéticos, sem impostos, taxas ou inflação.

## Atualização da V1
O aplicativo mantém a mesma chave de armazenamento `wealthpath_data_v1`, preservando registros ao atualizar **na mesma origem/URL e no mesmo navegador**, salvo limpeza de dados. Faça backup antes de substituir a versão anterior.
