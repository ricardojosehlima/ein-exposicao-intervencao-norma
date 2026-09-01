# EIN — Exposição e Intervenção na Norma

Portal estático pronto para GitHub Pages.

## Estrutura

- `index.html` — portal EIN
- `marcar-a-norma/` — conversor de marcação crítica da norma
- `escrever-brasileiro/` — conversor de formas brasileiras
- `assets/flags/` — PNGs públicos usados no modo de bandeira gráfica
- `cucagrafia/` — página provisória para configurar o link do site já existente da Cucagrafia

## Publicação

Publique o conteúdo desta pasta na raiz de um repositório GitHub e ative GitHub Pages. As páginas dos conversores calculam automaticamente as URLs HTTPS das bandeiras a partir do endereço em que forem publicadas.

## Teste das bandeiras gráficas

Depois de publicar por HTTPS:
1. abra um conversor;
2. selecione `Bandeiras: Gráficas`;
3. converta um texto que produza a bandeira;
4. clique em `Copiar resultado`;
5. cole no Google Docs e no Word.

A cópia rica utiliza uma URL pública PNG. A versão Unicode continua sendo enviada como fallback de texto simples.

## Cucagrafia

O endereço público não está configurado. Quando estiver disponível, substitua o link `./cucagrafia/` no card da home pelo endereço público, ou transforme `cucagrafia/index.html` em uma página de redirecionamento.
