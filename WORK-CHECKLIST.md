# Checklist de testes no ChatGPT Work — Biblioteca da Prof. Malu
Atualizado em 28/10/2026. Documento para execução interativa; a automação das 23h55 é um lembrete e não executa o Work.

## Atualização feita neste chat em 28/10/2026

**Documentação detalhada:** [PESQUISA-PAS-2026-10-28.md](PESQUISA-PAS-2026-10-28.md). Política editorial: apresentar aos alunos somente acessos gratuitos; quando não houver obra integral, sinalizar e convidar quem conhecer fonte autorizada a comunicar à professora.

- Fichas atualizadas no `pas-referencias.json` para 8 referências prioritárias; `index.html` agora apresenta `supportLinks` (múltiplos links por item) e consulta `pas-referencias.json?v=7`.
- **PAS 1 — insetos:** reportagem alternativa Superinteressante e notícia institucional da USP localizadas; HQ *Ciclos* atribuída a Luciano Queiroz/Marco Merlin; URL do autor identificada, mas seu carregamento expirou. Não considerar íntegra conferida.
- **PAS 1 — Divina Comédia HQ:** duas amostras oficiais documentadas; íntegra continua aguardando acesso de professores.
- **PAS 1 — Clermont e PAS 2 — Kant:** versões alternativas continuam expressamente sinalizadas; Clermont conta com fonte historiográfica universitária italiana; tradução de Floriano de Sousa Fernandes de Kant não localizada integralmente.
- **PAS 2 — Um inimigo do povo:** localizado site da produção da Cia. Código com ficha técnica e trailer; reprodução integral ainda sem validação.
- **PAS 2 — O burguês fidalgo:** sem gravação confirmada da apresentação indicada para Ribeirão Preto/2014; Parlapatões/2013 cadastrado apenas como **outra montagem**.
- **PAS 3 — Eles não usam Black-Tie / Vestido de Noiva:** links comerciais removidos das fichas; permanecem materiais acadêmicos gratuitos; texto integral gratuito e autorizado não confirmado e não redistribuído.
- **Não realizado neste chat:** inspeção de páginas de HQ que não carregaram, exibição integral das duas montagens, testes interativos reais em celular e computador e acesso de professores.
- **Atenção:** o PDF da UnB para PAS 2 e PAS 3 consultado no repositório está identificado como **versão preliminar de junho de 2024**; manter alerta editorial ao comparar com atualizações futuras.

## Testes adicionais de 28/10/2026 (segunda rodada)

**Registro detalhado:** [AUDITORIA-TECNICA-2026-10-28.md](AUDITORIA-TECNICA-2026-10-28.md).

- Integridade estrutural validada: **540 registros únicos**, sem IDs duplicados, URLs principais malformadas ou vínculos internos faltantes; mantidos 174 itens PAS e 4 módulos ProfHistória.
- GitHub Actions Pages: implantação do commit de referência `45f77ad4ccfbc67d4324e270f247c4ef7c0d83db` concluiu com `success`, run `40668052629`. O endereço público ainda não foi inspecionado em navegador real.
- **12 referências PAS com arquivos no Drive (9 arquivos distintos):** nomes, formatos e tamanhos localizados com conta autenticada; não foi testado acesso anônimo e não se conferiram conteúdo e licença. Identificação registrada nas fichas por `followUpTechnicalReview`.
- **7 referências PAS 1 de artes visuais:** páginas informativas Wikimedia/Wikipédia responderam; faltam inspeção exata de imagem e licença; não classificar como obra visual comprovada.
- **Constituição Federal PAS 1:** Planalto bloqueou a ferramenta de consulta, mas portal oficial da Câmara abriu e foi acrescentado como alternativa gratuita.
- **ENEM — Quarto de despejo:** removido link secundário para PDF sem autorização comprovada; empréstimo gratuito BibliON preservado.
- **Faltaram ao teste externo:** 3 referências de arte PAS 1 (Sankore, Serra da Capivara e mosaico de Teodora), Vimeo, reportagem G1 e verificação do Drive em navegador não autenticado. A amostra de links da Livraria da Câmara mostra opção de PDF gratuito mesmo quando a versão impressa é vendida; não orientar a compra.
- **Cache:** `leituras-enem.json?v=8` e `pas-referencias.json?v=7`.
- **Obras faltantes:** manter a busca suspensa nesta rodada por solicitação da usuária; retomar em alguns dias.

## 1. Site publicado
URL: https://malucesarrobot.github.io/Biblioteca-da-Prof-Malu/

Abrir no navegador real em desktop e largura de celular, sem depender da leitura da API GitHub. Confirmar carregamento de **catálogo de 540 fichas**, menu principal e as seções História, Sociologia, Ciências Sociais, Filosofia, PAS/UnB, Enem, Literatura, Teatro, BNCC, Curadoria temática e ProfHistória 2027. Validar teclado, busca, retorno, links externos, salvamento de leitura, acessibilidade visual, paginação, filtros e versões de cache depois de recarregar.

Se a página pública ainda não refletir commits do GitHub, verificar implantação do GitHub Pages, fonte do branch main e ausência de erro HTTP, sem concluir que os dados estão ausentes da API.

## 2. PAS — testar links com ressalvas
Arquivo completo e estruturado para execução em lote: `pas-pendentes-work.json` com **83 registros** (IDs, etapa, categoria, URLs e status). Há os seguintes agrupamentos:
- PAS 1 — Música: 13
- PAS 1 — Artes visuais: 11
- PAS 1 — Audiovisual: 9
- PAS 1 — Textos: 2
- PAS 2 — Literatura: 4
- PAS 2 — Audiovisual: 10
- PAS 2 — Música: 6
- PAS 2 — Artes visuais: 5
- PAS 3 — Audiovisual: 8
- PAS 3 — Música: 7
- PAS 3 — Teatro: 2
- PAS 3 — Artes visuais: 6

Prioridade máxima:
- PAS 3: *Eles não usam Black-Tie* (Moodle USP; PDF sem acesso integral confirmado) e *Vestido de Noiva* (Oficina de Teatro; página com botão de download, mas sem autorização de distribuição comprovada). **Não apresentar texto integral nem redistribuir arquivo protegido sem licença.**
- Textos e arquivos Google Drive que exijam autenticação, especialmente a reportagem G1 sobre o ciclo de vida dos insetos.
- Confrontar título, edição, autoria e tradução com a lista oficial (PAS 1 versão Cebraspe 2026; PAS 2 e 3 documentos indicados).
- Música/vídeo: conferir se os links levam exatamente à versão musical/audiovisual exigida, não apenas a outro vídeo do mesmo artista.
- Artes visuais: conferir imagem, legenda e atribuição; não substituir o original por foto de outra obra.
- Revisar amostra editorial identificada no PAS sem classificá-la como obra integral.

## 3. Acesso à obra e direitos
- Checar acesso livre real a *Darwinismo e racismo científico no Brasil* (SciELO Livros: https://books.scielo.org/id/2qpn8), que foi identificado bibliograficamente mas bloqueou acesso integral nesta sessão. Não cadastrar como PDF integral até obter a edição completa de fonte autorizada.
- Avaliar os PDFs históricos e universitários que tenham link de download mas não declaração de licença; acesso público não implica permissão de republicar.
- Verificar as fichas de empréstimo BibliON e bibliográficas Open Library das quatro obras contemporâneas sinalizadas.

## 4. Registre o resultado
Para cada link testado, registrar: ID, data, URL final, título do destino, acesso (integral/trecho/amostra/sem acesso), direitos/autorização (se conhecido) e uma descrição objetiva do erro, se houver. Atualizar `pas-referencias.json` ou a ficha correspondente SOMENTE após conferência individual. Preservar dados anteriores e usar commits descritivos.

## 5. Sem duplicar trabalho
Reutilizar `catalogo.json`, `curadoria-tematica.json`, `leituras-enem.json`, `pas-referencias.json`, `profhistoria-2027.json`. Não recriar `leituras.json`, arquivado em `historico/leituras-2026-10.json`. O catálogo conta 540 fichas; as 174 referências PAS não são mais 174 livros. A seleção ProfHistória 2027 é curadoria por quatro eixos, não bibliografia obrigatória.
