# Biblioteca da Prof. Malu — catálogo consolidado
Conferência editorial e técnica: 27/10/2026.

## Fontes de dados ativas
- `catalogo.json`: 288 livros/documentos, 102 artigos, 83 acervos/recursos e 7 apoios.
- `leituras-enem.json`: 10 fichas adicionais de leitura, integradas sem mudar a lista de obras obrigatórias do Enem (que não existe).
- `curadoria-tematica.json`: 45 fichas de livros/obras, 3 artigos, 1 recurso, 11 percursos temáticos, 3 patches de livros e 2 patches de artigos.
- `pas-referencias.json`: 174 referências, sendo 69 do PAS 1, 49 do PAS 2 e 56 do PAS 3. **Referência do PAS não equivale a obra integral disponível.**
- Total exibido pelo catálogo: **343 livros/documentos/volumes + 105 artigos + 91 recursos/apoios = 539 fichas**. As 174 referências PAS são uma lista adicional, com vínculos a fichas existentes, não 174 novos livros.

## Consolidação do cadastro antigo
O antigo `leituras.json` reunia 14 registros. Treze já existiam no catálogo ativo com fichas correspondentes. O 14º era um registro genérico da coleção `História Geral da África`, hoje representada por nove volumes individuais (I–VIII, X). Para preservar a procedência sem manter uma segunda fonte de cadastro, o antigo conteúdo foi arquivado em `historico/leituras-2026-10.json` e o arquivo redundante da raiz foi retirado.

A UNESCO informa que os volumes IX e XI foram concluídos internacionalmente, mas ainda não possuem edições em português disponibilizadas em sua página oficial; não os classificar como PDFs portugueses acessíveis até confirmação. Fonte: https://www.unesco.org/pt/general-history-africa

## Qualidade, acesso e direitos
- As 11 curadorias apontam para IDs existentes. Corrigida a atribuição de tema da pendência de Darwinismo e racismo científico.
- Os 174 itens PAS possuem URL; isso não certifica a abertura individual nem a leitura integral.
- Estados registrados no PAS: 81 links ainda não conferidos individualmente; 7 páginas sem confirmação de conteúdo integral; 1 amostra editorial; 1 peça cujo PDF não foi obtido. As demais fichas têm algum grau de conferência descrito individualmente, não equivalendo à verificação simultânea de todos os links.
- Fichas com trechos, coletâneas ou apenas versões externas de extensão incerta passaram a explicitar o **tipo de acesso**, sem afirmar que o livro todo esteja disponível.
- Quatro fichas do Enem/literatura indicavam PDFs externos de obras protegidas e não apresentavam comprovação de licença para distribuição gratuita; a situação foi sinalizada, sem declarar autorização inexistente. Preferir edições licenciadas e empréstimo bibliotecário.
- `Vestido de Noiva`: página externa de download localizada, mas direitos e arquivo integral não verificados. `Eles não usam Black-Tie`: página da USP localizada, PDF da peça não obtido. Nenhuma das duas deve ser apresentada como leitura integral verificada.

## Interface e integridade
- Biblioteca por áreas: História, Sociologia, Ciências Sociais e Filosofia.
- Seção de literatura: Romances, Contos e novelas, Poesia e **Teatro**, incluindo cinco fichas que já estavam cadastradas.
- Filtro PAS agora permite localizar acessos **não conferidos**, em vez de um filtro vazio para itens sem URL.
- Chaves de cache dos arquivos de dados atualizadas após a revisão.
- JSONs e sintaxe JavaScript devem ser validados após cada alteração; conferência no repositório não substitui teste visual em celular e computador.

## Pendências externas, não tratadas como falha de catalogação
1. Conferir individualmente links do PAS marcados como não verificados.
2. Confirmar edições/traduções exigidas (sobretudo Kant e peças teatrais).
3. Conferir licenças ou substituir PDFs de obras contemporâneas por acesso autorizado.
4. Abrir a página publicada e verificar navegação, filtros e acessibilidade visual em dispositivos reais.
