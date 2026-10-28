# Pesquisa complementar — 8 prioridades do PAS/UnB

**Data:** 28/10/2026  
**Escopo:** acesso legal, identificação de versões e montagens e fontes de apoio. Não é certificação de leitura integral nem licença de redistribuição.

## Resultado por item

| ID | Situação após pesquisa | Fonte/alternativa principal | O que ainda falta |
|---|---|---|---|
| `pas1_textos_4` | Reportagem alternativa aberta; HQ `Ciclos` identificada (Luciano Queiroz e Marco Merlin) | [Superinteressante](https://super.abril.com.br/ciencia/brasileiros-transformam-artigo-cientifico-sobre-insetos-em-hq/), [Jornal da USP](https://jornal.usp.br/ciencias/cientistas-e-cartunistas-se-unem-para-divulgar-ciencia-em-quadrinhos/), [site do autor](https://www.lucianoqueiroz.com.br/ciclos/) | G1 original bloqueou abertura; site da HQ expirou. Conferir visualmente as páginas no endereço oficial ou em fonte autorizada |
| `pas1_textos_5` | Duas amostras **oficiais**, nenhuma integral | [PDF amostra](https://www.editorapeiropolis.com.br/wp-content/uploads/2021/04/DC_LE_PDF__AMOSTRA.pdf), [amostra ePUB](https://digital.editorapeiropolis.com.br/epub-amostra/?id=6) | Aguardar acesso de professores para a HQ completa, preservando edição e adaptação |
| `pas1_textos_8` | Relatos históricos alternativos identificados | [Fordham (inglês)](https://sourcebooks.web.fordham.edu/source/urban2-5vers.asp), [Universidade de Nápoles (italiano)](https://www.rm.unina.it/didattica/fonti/anto_bme/cap_V/V_4.htm) | Identificar a versão e tradução específicas adotadas na avaliação; nenhuma é transcrição única e contemporânea do discurso |
| `pas2_textos_2` | Texto em português disponível em tradução **Luiz Paulo Rouanet** | [PDF já cadastrado](https://drive.google.com/file/d/1cCyWeLp8hP64XVHSd0LiYEjO82udLQ-p/view), [referência bibliográfica da tradução de Floriano de Sousa Fernandes em SciELO](https://www.scielo.br/j/trans/a/b5LGjhyvFjRQFqFHhtK8TLB/?lang=pt) | Localizar **a íntegra da tradução Floriano de Sousa Fernandes**, indicada na lista oficial; bibliografia não é o texto |
| `pas2_teatro_1` | **Montagem oficial da Cia. Código identificada** com ficha e trailer; PDF original da peça é material diferente | [Grupo Código — Inimigo do Povo](https://grupocodigo.org.br/inimigo-do-povo-2009/) | Conferir a gravação de 4/6/2019 exata e sua reprodução integral; trailer não equivale ao espetáculo |
| `pas2_teatro_2` | Montagem de **Ribeirão Preto, 13/04/2014**, citada pelo PAS, **não localizada com segurança**; outra montagem claramente sinalizada | [Parlapatões 2013 — alternativa](https://parlapatoes.com.br/site/o-burgues-fidalgo/), [lista oficial PAS 2, p. 9](https://pas.unb.br/images/pas/obras_de_referencia_pas_2.pdf#page=9) | Localizar o registro de **André Maurício Silva** correspondente ao Teatro Municipal de Ribeirão Preto; não substituir silenciosamente pela montagem de 2013 |
| `pas3_teatro_1` | PDF Moodle USP exige login; edição licenciada identificada | [Apple Books — e-book comercial](https://books.apple.com/br/book/eles-n%C3%A3o-usam-black-tie/id1302194787), [Record — editora](https://www.record.com.br/products/eles-nao-usam-black-tie), [BBM USP — vídeo de análise](https://bbm.usp.br/pt-br/videos/eles-n%C3%A3o-usam-black-tie/) | Acesso legítimo à íntegra (compra/empréstimo) ou autorização do arquivo; **não redistribuir** a obra protegida |
| `pas3_teatro_2` | Download de terceiro falhou; edição licenciada identificada | [Kobo — e-book comercial](https://www.kobo.com/br/pt/ebook/vestido-de-noiva-2), [Nova Fronteira — editora](https://www.novafronteira.com.br/vestido-de-noiva), [USP — ficha bibliográfica](https://bctb.eca.usp.br/obra.php?cod=9743) | Acesso legítimo ao texto completo; não assumir que arquivo de terceiro tem licença de distribuição |

## Decisões editoriais aplicadas

1. URLs e fichas originais preservadas em `pas-referencias.json`, com notas e fontes alternativas.
2. Foram diferenciados **texto dramático**, **montagem específica**, **trailer**, **estudo acadêmico**, **amostra**, **e-book comercial** e **obra integral**.
3. A página `index.html` passou a renderizar `supportLinks` para uma referência do PAS ter vários caminhos qualificados, sem confundir a fonte oficial com versões complementares.
4. A versão de cache de `pas-referencias.json` passou de 4 para 5 para estimular o recarregamento dos novos registros.
5. Nenhum PDF protegido foi baixado ou republicado no GitHub.

## Atenções

- O arquivo `auditoria-pas-2026-10-28.json` registra **83 testes técnicos**, 60 respostas e 23 erros anteriores; tais números não são número de obras faltantes.
- O cruzamento `cruzamento-listas-pas-2026-10-28.json` encontrou **174 correspondências de títulos** nas três listas de referência, não 174 obras integrais.
- **A Divina Comédia — HQ** permanece dependente de acesso de professores, conforme orientação anterior.
- A auditoria do site em celular, testes de autenticação, reprodução integral de vídeos e visualização de ilustrações continuam no `WORK-CHECKLIST.md`.

## Fontes primárias e institucionais adicionais

- [PAS 2: obras de referência — UnB](https://pas.unb.br/images/pas/obras_de_referencia_pas_2.pdf).
- [Cia. Código: ficha técnica da montagem](https://grupocodigo.org.br/inimigo-do-povo-2009/).
- [Jornal da USP: notícia sobre a HQ Ciclos](https://jornal.usp.br/ciencias/cientistas-e-cartunistas-se-unem-para-divulgar-ciencia-em-quadrinhos/).
- [Editora Peirópolis: curadoria Clássicos em HQ](https://blog.editorapeiropolis.com.br/curadoria-classicos-em-hq/).
- [Biblioteca de Teatro da USP: Vestido de noiva](https://bctb.eca.usp.br/obra.php?cod=9743).
