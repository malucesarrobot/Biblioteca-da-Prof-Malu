# Auditoria técnica — segunda rodada da Biblioteca da Prof. Malu

**Data:** 28/10/2026. **Escopo:** testes de integridade, metadados de arquivos, disponibilidade de páginas públicas e identificação de licenças. **Não** substitui testes de reprodução audiovisual, leitura de PDFs ou verificação em dispositivos reais.

## 1. Catálogo e referências

- 288 livros e documentos + 102 artigos + 83 recursos + 7 apoios no catálogo principal.
- 46 livros + 3 artigos + 1 recurso da curadoria temática; mais 10 leituras Enem; 540 registros **únicos** na fusão de fontes ativas.
- 174 referências PAS (69, 49, 56) e 4 eixos ProfHistória.
- Não foram encontrados IDs duplicados na fusão de registros, links principais com prefixo malformado nem IDs de curadorias/PAS/ProfHistória sem ficha correspondente.
- Inspeção sintática e estrutural de dados não equivale a garantir que todos os 540 links funcionam.

## 2. Publicação

A execução de GitHub Pages [40668052629](https://github.com/malucesarrobot/Biblioteca-da-Prof-Malu/actions/runs/40668052629) concluiu com sucesso em 28/10/2026, após o commit `45f77ad4ccfbc67d4324e270f247c4ef7c0d83db`. A ferramenta de consulta web não abriu `https://malucesarrobot.github.io/Biblioteca-da-Prof-Malu/`; isso não indica, por si, falha do site. Falta navegar em celular e desktop, com testes de filtros, retorno, foco, salvamento local e cache.

## 3. Links externos anteriormente sem confirmação

- Sete páginas da Wikipédia/Wikimedia Commons abriram e exibiram conteúdo textual compatível com os temas: Manto Tupinambá (`pas1_artes_visuais_1`), Nebamun e Ipuki (`5`), Grupo de Laocoonte (`6`), Coliseu (`7`), Juízo Final de Vasari e Zuccari (`9`), Cúpula de Santa Maria del Fiore (`10`) e Igreja de São Jorge, Lalibela (`11`). **Não** foi avaliada a fotografia exata indicada na lista nem sua licença.
- O [portal legislativo da Câmara dos Deputados](https://www2.camara.leg.br/a-camara/atividade-legislativa/legislacao/constituicao1988) abriu com opções de leitura em HTML e download gratuito; apresenta atualização até EC 141/2026. O link Planalto retornou bloqueio da ferramenta. Foi registrada fonte alternativa em `pas1_textos_14`.
- Metadados autenticados do Google Drive confirmaram **9 arquivos diferentes associados a 12 referências**. PAS 2: antologia literária compartilhada por 4 referências, 4 PDFs de arte e 1 JPEG de arte; PAS 3: 3 PDFs de artes visuais. Google informou nome, formato e tamanho. A flag de compartilhamento não comprova acesso público anônimo nem autoriza redistribuição.
- Vimeo (`pas2_audiovisual_1`) permaneceu inacessível por esta ferramenta. A reportagem original do G1 (`pas1_textos_4`) continua sem validação integral.
- Permanecem sem teste de páginas de imagem: Sankore (`pas1_artes_visuais_2`), arte rupestre da Serra da Capivara (`pas1_artes_visuais_4`) e mosaico de Teodora (`pas1_artes_visuais_8`).
- A auditoria anterior tem **83 testes técnicos, 60 respostas e 23 erros**. A nova rodada registra evidências complementares, mas **não altera retroativamente** aquele resultado, nem permite inferir que 23 links estejam hoje quebrados.

## 4. Livraria da Câmara e acesso gratuito

Nas páginas examinadas de *Úrsula e outras obras*, *Dom Casmurro*, *Memórias Póstumas de Brás Cubas*, *O Cortiço*, *Macunaíma*, *Senhora*, *Iracema*, *O Abolicionismo* e em outros títulos, foi identificado o comando **BAIXE GRÁTIS** com alternativa PDF/ePUB, mesmo quando há botão separado para compra de versão impressa. Os registros do catálogo que apontam para essas páginas **não exigem pagamento para o arquivo digital**. Nem todas as edições Câmara foram abertas individualmente; duas consultas apresentaram timeout e outras indisponibilidade desta ferramenta. Priorizar, quando possível, links diretos à edição digital gratuita para evitar confusão.

## 5. Correções efetuadas

- `leituras-enem.json`: removido link secundário de PDF avulso de *Quarto de despejo* sem comprovação de licença de circulação aberta; mantido empréstimo digital gratuito na BibliON.
- `pas-referencias.json`: acrescentado acesso alternativo gratuito à Constituição pela Câmara e `followUpTechnicalReview` às 20 referências (12 referências do Drive, 7 páginas Wikimedia, 1 Constituição).
- `index.html`: versões de cache incrementadas para PAS e Enem; demais fontes e estrutura preservadas.

## 6. Pendente para teste visual real

1. Página publicada: comportamento em desktop/celular, navegação por teclado e leitor de tela, filtros, links e armazenamento local.
2. Abrir arquivos Google Drive sem autenticação e verificar cada obra/imagem, sem pressupor licença pela existência do arquivo.
3. Confirmar versões de vídeos e músicas, fotografias correspondentes às obras e PDF integral quando houver autorização.
4. Não retomar nesta rodada as oito obras/versões do PAS que foram reservadas para pesquisa em alguns dias.
