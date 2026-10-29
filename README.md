# Biblioteca da Prof. Malu — catálogo consolidado

**Política de acesso:** priorizar exclusivamente links gratuitos para estudantes, distinguindo amostras, trechos e obras integrais. Quando não houver acesso integral gratuito e autorizado, sinalizar a lacuna sem divulgar links de compra. Alunos que tenham ou conheçam acervos gratuitos e legalmente compartilháveis podem informar à professora Malu a obra e a fonte, para conferência antes da inclusão.
Conferência editorial e técnica: 27/10/2026.

## Fontes de dados ativas
- `catalogo.json`: 288 livros/documentos, 102 artigos, 83 acervos/recursos e 7 apoios.
- `leituras-enem.json`: 10 fichas adicionais de leitura, com acessos comerciais não licenciados substituídos por empréstimo ou referência bibliográfica, integradas sem mudar a lista de obras obrigatórias do Enem (que não existe).
- `curadoria-tematica.json`: 46 fichas de livros/obras, 3 artigos, 1 recurso, 11 percursos temáticos, 3 patches de livros e 2 patches de artigos.
- `pas-referencias.json`: 174 referências, sendo 69 do PAS 1, 49 do PAS 2 e 56 do PAS 3. **Referência do PAS não equivale a obra integral disponível.**
- `profhistoria-2027.json`: quatro eixos do Anexo 4 do Exame Nacional de Acesso 2027; vincula 15 livros/documentos e 18 artigos já cadastrados, sem duplicar fichas.
- **Fontes oficiais ProfHistória 2027:** edital, anexos da seleção, catálogo de disciplinas com 53 páginas, provas anteriores e dissertações UFG; lista de links conferidos em [`PROFHISTORIA-FONTES-OFICIAIS-2027.md`](PROFHISTORIA-FONTES-OFICIAIS-2027.md). O catálogo curricular não equivale à bibliografia obrigatória da prova.
- Total exibido pelo catálogo: **344 livros/documentos/volumes + 105 artigos + 91 recursos/apoios = 540 fichas**. As 174 referências PAS são uma lista adicional, com vínculos a fichas existentes, não 174 novos livros.

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

## Revisão adicional de fontes (27/10/2026)
- John Reed, *Dez dias que abalaram o mundo*: acrescentado à curadoria. PDF de 270 páginas hospedado pelo PSTU, tradução de José Octávio identificada; autorização de redistribuição da tradução não verificada. A página do Marxists Internet Archive tem índice e aviso de licença da versão galega, mas não disponibilizou capítulos completos nesta consulta.
- *Darwinismo e racismo científico no Brasil* (UEFS, 2023, 98 p.): dados e sumário conferidos no SciELO Livros. A consulta ao livro retornou bloqueio 403; livre acesso integral não afirmado.
- Confirmada a diferença entre a lista PAS 1 divulgada em 2025 e a edição atualizada do Cebraspe em 2026. Mantida a lista atual de 69 itens do PAS 1.
- Conferidos os textos de Pesquisa FAPESP (linguagem humana, rio São Francisco), SciELO (crise Yanomami, atividade antioxidante do cerrado), El País (entrevista de Bauman) e Revista de Estudos e Pesquisas sobre as Américas da UnB (Lélia Gonzalez). O G1 não permitiu abrir a reportagem de insetos nesta consulta.
- Substituídos quatro links externos de PDFs contemporâneos sem autorização comprovada: *A revolução dos bichos* passou a empréstimo da BibliON; *A hora da estrela* direciona à busca na BibliON; *O mundo de Sofia* e *O código Da Vinci* passaram a fichas editoriais da Open Library, sem promessa de leitura integral gratuita.
- A conferência automatizada de URLs de música, audiovisual, imagens e Google Drive continua limitada por restrições de acesso das plataformas. Os registros não devem ser rotulados como efetivamente abertos enquanto não houver teste individual.

## Teatro do PAS 3 — acesso e direitos
- *Eles não usam black-tie*: arquivo da USP não foi obtido; adicionada referência à análise de Iná Camargo Costa publicada no periódico acadêmico Discurso/USP, sem apresentá-la como texto dramático.
- *Vestido de noiva*: o Oficina de Teatro publica um botão de download e indica um arquivo de 168,5 KB, mas o campo licença está vazio. Adicionada ficha bibliográfica da USP. A disponibilidade do download não prova autorização de distribuição da peça protegida.

## ProfHistória — lista nominal de textos integrais gratuitos, 29/10/2026
- Página nova `#integrais-profhistoria`: **1 livro integral + 29 artigos científicos completos** que constam das bibliografias do mestrado, com busca e fonte original, e **3 trabalhos acadêmicos completos** separados no filtro (1 tese e 2 dissertações).
- Lista documental para revisão e cópia: [RELACAO-TEXTOS-INTEGRAIS-PROFHISTORIA-2026-10-29.md](RELACAO-TEXTOS-INTEGRAIS-PROFHISTORIA-2026-10-29.md).
- Gersem Baniwa, *O índio brasileiro*: PDF gratuito [no portal oficial da Funai](https://biblioteca.funai.gov.br/media/pdf/LIVROS/MFN-21340.pdf). Ficha do livro aponta igualmente para o LACED/Museu Nacional.
- Todos os títulos com acesso gratuito identificado; a disponibilidade em navegador anônimo de cada arquivo ainda deve ser acompanhada. A lista não substitui o catálogo integral do mestrado nem incorpora indevidamente os 24 textos de apoio da seleção como bibliografia curricular.

## ProfHistória — sexta rodada e downloads, 29/10/2026
- **Downloads dos cinco materiais solicitados:** PDFs de Ana Maria Mauad (UFF), Joan Scott (PUC-SP), François Hartog (SciELO) e Circe Bittencourt (SciELO), mais dissertação e catálogo pedagógico de Evelyn Lucena Machado (eduCAPES). As fichas agora mostram "Abrir/Baixar PDF" quando há URL de arquivo; os arquivos seguem hospedados nas fontes oficiais.
- **Bibliografia curricular do mestrado:** 33 referências gratuitas em 13 disciplinas. Livros ainda sem acesso integral autorizado ficam fora da oferta pública.
- **Seleção e formação:** 24 leituras gratuitas de apoio, distinguindo materiais citados nas provas, artigos dos autores, estudos sobre suas teorias e materiais de doutorado (não mestrado).
- **Dissertações da rede:** 13 pesquisas e produtos educacionais em universidades ProfHistória, em página separada `#pesquisas-profhistoria`; duas dissertações adicionais da UFG (outro programa) continuam explicitamente diferenciadas.
- **Sexta rodada:** 5 artigos de UDESC, UFSC e UFSM e 6 dissertações de UFF, UERJ e UFRR. Relatório completo [PESQUISA-PROFHISTORIA-SEXTA-RODADA-2026-10-29.md](PESQUISA-PROFHISTORIA-SEXTA-RODADA-2026-10-29.md).
- **Não inventar acervo:** nenhum título sem acesso gratuito deve aparecer como opção de leitura; o catálogo curricular do mestrado não é bibliografia obrigatória da seleção. Permanecem pendentes os testes visuais de navegador anônimo e celular.

## Acervos acadêmicos de universidades integrantes do ProfHistória — 28/10/2026
- Nova página pública: `#pesquisas-profhistoria`. Reúne **7 dissertações e produtos educacionais do ProfHistória**, de **UERJ, UFRJ, Unespar, UFMT, UFRRJ, UFSC e UFG**, localizados em eduCAPES e repositórios institucionais; arquivos gratuitos ofertados pelas instituições.
- Em seção claramente diferenciada, **2 dissertações do Mestrado em História da UFG** estudam as teorias de Paul Ricoeur; NÃO são produção do ProfHistória nem livros originais de Ricoeur.
- A seleção `#profhistoria` foi ampliada de 13 para **15 textos gratuitos**, com texto original de Roger Chartier disponível no repositório da UFSC e artigo de Ana Maria Monteiro e Luciana Rossato publicado pela UERJ.
- **Bibliografia do curso:** permanece em **21 textos gratuitos** distribuídos em **9 disciplinas**. Nenhum novo item sem acesso livre foi incluído; dissertações da rede não são apresentadas como se integrassem a bibliografia obrigatória de ingresso.
- Relatório detalhado e distinção das fontes: [PESQUISA-PROFHISTORIA-ACERVOS-UNIVERSIDADES-2026-10-28.md](PESQUISA-PROFHISTORIA-ACERVOS-UNIVERSIDADES-2026-10-28.md).
- Os livros integrais de Koselleck, Ricoeur, Chartier, Circe Bittencourt e Ana Maria Monteiro seguem sem edição digital livre autorizada localizada. Nenhuma ficha os anuncia como integralmente disponíveis.

## ProfHistória 2027 — seção própria
Página no site: `#profhistoria`. Baseada no Anexo 4 da seleção oficial: https://selecao.econrio.com.br/modulo/arquivos/26167/inscricao/edital/26167_-_anexo_4_-_conteu%CC%81dos_programa%CC%81ticos.pdf
- (a) Construção do conhecimento histórico: fatos, documentos, narrativas e ensino;
- (b) Tempos históricos: percepções do tempo, ritmos, rupturas e periodizações;
- (c) História, memória e identidade: dever de memória, esquecimentos, patrimônio;
- (d) Ensino de História, cidadania e diversidade cultural: currículo, política, mídias e formação docente.
A bibliografia exibida é seleção editorial a partir do catálogo, não livros obrigatórios do edital.
Organizadora: https://econrio.com.br/index.php/course/mestrado-profissional-em-ensino-de-historia-profhistoria-2027/ — inscrições 26/08 a 17/11/2026 e prova em 06/12/2026.

## Limites da validação e tarefas para Work
- Conferência de código e dados após as alterações: **540 fichas, 174 referências PAS, 4 eixos ProfHistória**; nenhum ID duplicado, ausência de campo essencial ou referência interna sem registro. Scripts JavaScript compilam sintaticamente. Esse resultado não equivale a teste de interface no navegador.
- A lista de **83 links PAS ainda sujeitos a inspeção interativa**, incluindo vídeo, áudio, obras visuais, Google Drive e teatro, foi consolidada em `pas-pendentes-work.json`.
- O procedimento com verificações visuais (desktop e celular), downloads, redirecionamentos, autenticação, filtros e licenças está descrito em `WORK-CHECKLIST.md`. A automação das 23h55 apenas lembra de usar o Work para executar esses testes.
- O acesso ao domínio GitHub Pages publicado não foi comprovado nesta consulta; não confundir repositório atualizado com interface web renderizada e testada.
- *Darwinismo e racismo científico no Brasil* continua registrado em `curadoria-tematica.json.pending`, com dados editoriais, mas sem PDF integral gratuito confirmado por fonte autorizada.

## Escolha de idioma e contador de acessos (29/10/2026)
- Na estante de livros (`#livros`) e no atalho `#idiomas`, o filtro **Todos os idiomas** lista somente idiomas efetivamente registrados nas fichas. Obras cadastradas como bilíngues ou multilíngues aparecem nos filtros pertinentes. O filtro não traduz obras automaticamente nem presume a existência de versões adicionais.
- Cada cartão e cada ficha de livro indicam o idioma da edição ou as ressalvas informadas no cadastro. Idiomas não informados são identificados como **Não informado**.
- O rodapé exibe a **contagem de aberturas da página**, não visitantes únicos; atualizar a página pode produzir nova contagem. O navegador consulta o serviço externo CounterAPI (`counterapi.com`) por `fetch` com `credentials: 'omit'`, sem enviar, gravar ou exigir cookies para o contador. O serviço informa anonimizar dados técnicos em sua própria infraestrutura; a biblioteca não obtém identificadores individuais.
- Se a API do contador falhar ou estiver bloqueada, o rodapé mostra **indisponível**, sem fabricar números. Essa integração externa deve ser conferida no site publicado.
