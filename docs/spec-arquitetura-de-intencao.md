# Trilha "Arquitetura de Intenção" — Blueprint (4 dias)

> Curso HTML self-contained no padrão **INEMA.CLUB `formato-curso-v2`** (camada de
> aprendizagem: progresso, marcar lido, dúvida, anotação/highlight, "minha jornada",
> export/import, temas, modo leitura). Serve também de **roteiro para o curso presencial**.

## Tese central
**Prompt não basta.** A nova habilidade não é "usar IA" — é **arquitetar intenção**:
estruturar contexto, regras, memória, objetivos e critérios de validação para que a IA
transforme intenção em resultado **confiável, repetível e alinhado**. A diferença entre
quem usa IA no raso e quem constrói sistema é a mesma entre **improvisar e projetar**.

## Público e profundidade
- **Público:** criadores, empreendedores, gestores, educadores e devs que querem sair do
  uso superficial da IA. Não exige saber programar.
- **Profundidade:** didático + **mão na massa**. Cada dia entrega algo aplicável. Conteúdo
  estruturado para servir de **material do facilitador** no presencial.

## A Pirâmide (espinha dorsal mental — ilustração central, SVG)
Escada evolutiva, da base ao topo:
1. **Coding** — o humano escreve cada linha; controla toda a lógica.
2. **Vibe Coding** — o humano descreve a intenção; a IA gera a 1ª solução.
3. **Engenharia Agêntica** — a IA executa em ciclos (escreve, testa, corrige, entrega); o humano **dirige**.
4. **Arquitetura de Intenção** — o foco sai do agente e vai para **o sistema que orienta o agente**.

A pergunta muda de *"como faço um prompt melhor?"* para *"como estruturo uma inteligência
operacional para resultados confiáveis, repetíveis e alinhados?"*

## Os 5 Pilares da Arquitetura de Intenção
1. **Contexto** — o que a IA precisa saber. (Limite: contexto sem objetivo vira excesso.)
2. **Objetivos** — o que é sucesso e por quê.
3. **Regras** — limites de operação. (Automação sem regra vira risco.)
4. **Memória** — padrões e conhecimento que persistem entre execuções.
5. **Validação** — como saber se o resultado está certo. (IA sem validação vira ilusão de produtividade.)

A cadeia: **Intenção → Contexto → Processo → Resultado.**
Os 4 colapsos do uso raso: intenção sem estrutura = ruído · contexto sem objetivo = excesso ·
automação sem regra = risco · IA sem validação = ilusão de produtividade.

## Fio condutor (caso real único, atravessa os 3 dias)
Caso-âncora demonstrado por completo: **"Assistente de atendimento ao cliente de um negócio"**
(universal, mostra os 5 pilares com clareza). Cada aluno escolhe **sua própria intenção real**
no Dia 1 e a desenvolve até virar sistema no Dia 3. Exemplos prontos adicionais em outros
domínios (conteúdo/marca, planejamento de produto, automação) para não prender a uma vertical.

## Estrutura de arquivos
- `index.html` — landing da trilha: hero com a pirâmide, os 3 dias como módulos, "o que você
  vai aprender", pré-requisitos, CTA INEMA.CLUB.
- `dia-1.html`, `dia-2.html`, `dia-3.html`, `dia-4.html` — uma página por dia.
- Tudo self-contained (HTML + Tailwind CDN + JS inline), abre em `file://`, padrão v2.

## Arco dos 3 dias
Cada dia tem: **objetivos de aprendizagem · conceito (com ilustração SVG clara) · exemplos
prontos · 1+ exercício prático com gabarito · 1 template reutilizável · bloco "para facilitar
ao vivo" (tempo + dinâmica de grupo) · entregável do dia.**

### Dia 1 — A Pirâmide: por que o prompt não basta  *(ver + diagnosticar)*
- As 4 camadas e o que muda em cada uma (quem faz o quê; o papel do humano sobe).
- Improvisar × projetar; depender da sorte × construir sistema.
- Os 4 sintomas do uso raso (com exemplo de cada).
- **Exercícios:** (a) autodiagnóstico "onde estou na pirâmide"; (b) reescrever um prompt solto
  identificando o que falta; (c) escolher 1 intenção real para os 3 dias.
- **Template:** "Mapa de Posição na Pirâmide".
- **Entregável:** mapa preenchido + 1 intenção real escolhida.

### Dia 2 — Os 5 Pilares: estruturar a intenção  *(o método, mão na massa)*
- Um bloco por pilar: definição · ilustração · exemplo **bom × ruim** · template/prompt-mãe.
- A cadeia Intenção → Contexto → Processo → Resultado (ilustração).
- **Exercícios:** preencher cada pilar para a intenção do Dia 1; comparar par bom×ruim.
- **Template:** **Canvas de Arquitetura de Intenção** (os 5 pilares em 1 folha).
- **Entregável:** Canvas preenchido para o caso real do aluno.

### Dia 3 — O Sistema: de intenção a resultado confiável  *(montar + operar)*
- De peças soltas a sistema: frameworks, fluxos, agentes, memória.
- O ciclo de operação: **rodar → validar → ajustar → melhorar** (ilustração de loop).
- A lógica acima das ferramentas (ferramentas mudam; a lógica fica).
- **Exercícios:** montar o sistema a partir do Canvas; rodar 1 ciclo de validação; definir
  melhoria contínua.
- **Template:** "Ficha do Sistema" + checklist de validação.
- **Entregável/"certificado":** 1º sistema de Arquitetura de Intenção funcionando + plano de melhoria.

## Requisitos visuais
- **Desenhos ilustrativos claros** em SVG (estilo futurista dark premium âmbar/ciano do v2):
  a pirâmide (4 camadas), os 5 pilares, a cadeia Intenção→Resultado, o loop de validação,
  bom×ruim, e o "antes×depois" (raso × estruturado).
- Muitos **exercícios práticos** e **exemplos prontos** (worked examples) — densidade alta.

## Camada de aprendizagem (v2)
Progresso/marcar-lido, dúvida, anotações/highlight no texto, painel "minha jornada"
(continuar de onde parei), export/import `.json`, temas trocáveis + preferências de leitura.

### Dia 4 — A Virada: modelos que operam na intenção  *(subtrair + migrar — adicionado em 2026-09-06)*
Contexto: em set/2026 saíram o Claude Fable 5.1 (Anthropic, 1/set) e o GPT-6 Astra (OpenAI, 3–4/set).
Os guias oficiais dizem que instruções escritas para modelos anteriores "são prescritivas demais e
degradam a qualidade" (Anthropic) e que skills/AGENTS.md acumularam "gordura" (equipe do Codex/OpenAI).
- T1 O que mudou em set/2026: fatos e datas; erros opostos (Fable age além / Astra para e pergunta)
  com a mesma causa; os 5 pilares mudam de forma, não caem.
- T2 Engenharia por subtração: pergunta de corte linha a linha; checklist de auditoria; permissão com cerca.
- T3 Fronteiras, não passos: pilar Autoridade; as três paradas (irreversível / escopo / só o usuário sabe);
  suposição declarada; garantia fora do texto.
- T4 Definição de pronto e verificação com evidência: prompt de seis partes; "poder fazer ≠ ter feito";
  verificador separado; último parágrafo não é promessa.
- T5 Esforço, memória e trabalho longo: cinco níveis; "coisa mais simples que funcione"; pasta de lições
  (uma por arquivo); ritmo de atualização; delegação; custo de cache.
- T6 Projeto: migrar a Ficha do Sistema (dia 3) para a Ficha de Intenção v2 e rodar o mesmo caso nos dois
  formatos (tabela de comparação).
- Template: Ficha de Intenção v2 + tabela de comparação. Fontes datadas (5/set/2026) no fim da página.
- Entregável: Ficha v2 datada + comparação v1 × v2 no caso real. Reauditar a cada nova geração.
