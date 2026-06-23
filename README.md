# Ficha Cadastral – Novaplast

Formulário web de cadastro de clientes da Novaplast, hospedado via GitHub Pages.

## Acesso

O formulário está disponível em:
**https://bruno0405.github.io/Faturamento/**

## Funcionalidades

- Cadastro para três tipos de cliente: Pessoa Física, Pessoa Jurídica e Produtor Rural
- Campos condicionais — cada tipo exibe apenas os campos necessários
- Validação de CPF, CNPJ, e-mail e campos obrigatórios
- Upload de documentos (RG, CPF, Contrato Social, foto)
- Envio automático por e-mail para a equipe de faturamento via Formspree

## Arquivos

| Arquivo | Descrição |
|---|---|
| `index.html` | Formulário completo (HTML + CSS + JavaScript) |
| `DOCUMENTACAO.md` | Documentação técnica para manutenção e alterações |
| `GUIA_FATURAMENTO.md` | Guia de uso para a equipe de faturamento |
| `README.md` | Este arquivo |

## Documentação

Para alterar campos, cores, limites de upload ou configurações do Formspree, consulte o arquivo `DOCUMENTACAO.md`.

Para dúvidas sobre como receber e interpretar os cadastros, a equipe de faturamento pode consultar o `GUIA_FATURAMENTO.md`.

## Tecnologias utilizadas

- HTML, CSS e JavaScript puro (sem frameworks)
- [Formspree](https://formspree.io) para envio de e-mail com anexos
- GitHub Pages para hospedagem
