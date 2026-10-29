# Contratos Lumatec

Gerador de contratos de prestação de serviços com base no modelo da Lumatec Climatização. O texto do contrato já vem pronto. Você preenche só o que muda de um contrato para outro e baixa o PDF final.

## O que dá para editar

- **Contratada:** Lumatec por padrão. Você pode salvar outras empresas, cada uma com o próprio logo.
- **Contratante:** pessoa jurídica ou física, com validação de CNPJ e CPF.
- **Objeto:** a lista de serviços.
- **Valores:** total, de 1 a 12 parcelas (divididas igualmente ou manualmente) e forma de pagamento.
- **Prazos:** etapas em dias úteis ou corridos.
- **Condições:** juros, multa, honorários, índice de correção e garantia.
- **Cláusulas:** biblioteca para ligar e desligar, mais cláusulas livres.
- **Fecho:** título, cidade, data, foro, vias e testemunhas.

A numeração das cláusulas, as referências entre elas e os valores por extenso se ajustam sozinhos.

## Como usar

Abra o `index.html` no navegador ou acesse a versão publicada. O rascunho e as empresas salvas ficam no navegador de quem usa (localStorage).

## Tecnologia

Um único arquivo HTML, sem etapa de build. O PDF é gerado no navegador com [pdfmake](https://pdfmake.github.io/docs/) 0.2.7, carregado pelo jsDelivr.

## Aviso

Este repositório é uma ferramenta de apoio. O texto das cláusulas, principalmente as marcadas como "extra", deve ser revisado por um advogado antes do uso.
