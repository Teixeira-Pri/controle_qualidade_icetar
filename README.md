# Controle de Qualidade — ICETAR

Sistema de controle de qualidade desenvolvido para uso interno da **ICETAR — Indústria e Comércio de Equipamentos de Tratamento de Ar**.

## Sobre o projeto

Formulário digital para registro e acompanhamento da inspeção de qualidade de secadores por adsorção regeneração a frio, substituindo o processo manual em papel.

O relatório reúne em uma única tela:

- Dados gerais do equipamento (série, produto, destinatário, nota fiscal)
- Folha de dados técnicos (dimensões, capacidade, tensão, conexões)
- Tabela de inspeção com 19 itens avaliados (APR / REP / OBS)
- Teste de ciclo da máquina (Ciclo A e B)
- Observações gerais e modelo de filtro
- Responsáveis pela montagem e pelo controle de qualidade
- Assinatura digital do responsável ICETAR
- Geração de PDF diretamente pelo navegador
- Marca d'água ICETAR em todas as páginas do relatório

## Acesso restrito

Este sistema é de **uso exclusivo da equipe interna da ICETAR**. Por isso, o acesso é protegido por senha — armazenada em hash SHA-256 no cliente, sem transmissão de dados a servidores externos.

O projeto é hospedado via GitHub Pages apenas para facilitar o acesso interno sem necessidade de infraestrutura adicional.

## Tecnologias

- HTML5, CSS3 e JavaScript puro (sem frameworks ou dependências externas)
- Fontes: [Barlow](https://fonts.google.com/specimen/Barlow) e [Barlow Condensed](https://fonts.google.com/specimen/Barlow+Condensed) via Google Fonts
- Assinatura digital via Canvas API
- Hash de senha via Web Crypto API (SHA-256)
- Geração de PDF via `window.print()`

## Empresa

**ICETAR — Indústria e Comércio de Equipamentos de Tratamento de Ar**  
Rua Ibituruna, 961 – Parque Imperial, São Paulo – SP  
Tel. (11) 5071-2395 | [www.icetar.com.br](http://www.icetar.com.br)
