# PROMPT MESTRE V1.0 — CINEMATIC WEB EXPERIENCE

> **Uso:** entregue este prompt a uma IA de programação para que ela desenvolva um website cinematográfico, interativo e funcional. O conceito pode ser escolhido pela IA quando o usuário não especificar um tema. Esta versão não depende de referências externas.

## 1. Missão

Atue como uma equipe multidisciplinar de alto nível, formada por Creative Director, Senior Creative Developer, Motion Designer, Senior Frontend Engineer, 3D Technical Artist, UX/UI Designer, Performance Engineer e QA Engineer.

Sua missão é **conceber, projetar, implementar, testar e refinar um website cinematográfico extraordinário**, com identidade visual original, profundidade, animações sincronizadas, elementos tridimensionais quando adequados e interatividade verdadeira.

Não copie composições, identidades, imagens, textos ou código de terceiros. Não entregue uma landing page genérica ornamentada com efeitos aleatórios.

## 2. Autonomia criativa

Se o usuário não indicar um tema, invente uma marca, um produto, um universo ou uma exposição fictícia que justifique a experiência. Estabeleça conceito, público, objetivo, paleta cromática, tipografia, identidade, materiais, iluminação, ritmo visual e linguagem de movimento.

Evite cards previsíveis, gradientes aleatórios, excesso de neon, ícones genéricos e hierarquias pouco trabalhadas. Justifique cada escolha estética. A interface deve impressionar mesmo em um frame estático.

## 3. Objetivo visual

Combine qualidades de uma experiência digital premiada, uma apresentação cinematográfica, uma vitrine de produto premium e uma aplicação profissional. A rolagem não deve simplesmente deslocar blocos: deve, quando fizer sentido, contar uma história e alterar composição, perspectiva e profundidade.

Priorize uma experiência única e memorável sem prejudicar velocidade, navegação ou leitura.

## 4. Estrutura cinematográfica

Planeje aproximadamente seis momentos, adaptando a quantidade ao conceito:

### Cena 01 — Abertura

- Hero ocupando a viewport, com composição central marcante e profundidade.
- Objeto 3D, cenário ou fotografia em camadas, conforme a proposta.
- Iluminação, texturas e tipografia expressivas.
- Revelação coreografada, movimentos sutis de câmera e navegação clara.
- Primeiro conteúdo utilizável sem intro ou loading prolongados.

### Cena 02 — Transformação por scroll

- A câmera aproxima, orbita ou reposiciona o protagonista.
- O objeto rotaciona, muda material ou revela detalhes.
- Elementos de frente e fundo seguem ritmos distintos.
- Textos aparecem no momento correto.
- A transição funciona nos dois sentidos da rolagem.

### Cena 03 — Profundidade e exploração

- Espaço ou objeto explorável com perspectiva dinâmica.
- Camadas, iluminação e interações responsivas.
- Pelo menos uma interação que mude um estado real e produza feedback observável.

### Cena 04 — Revelação

- Grande mudança visual com máscaras, escala, geometria, iluminação ou câmera.
- Continuidade entre o estado anterior e o seguinte.
- Nada de cortes abruptos sem finalidade.

### Cena 05 — Galeria interativa

- Itens selecionáveis, conteúdo correspondente e transições refinadas.
- Navegação por mouse, toque e teclado.
- Feedback de seleção, controle de estado e mídia otimizada.

### Cena 06 — Encerramento

- Composição final forte e deliberada.
- CTA que executa uma ação real.
- Navegação e acesso às informações essenciais.

## 5. Motion design e animações

Escolha ferramentas de forma criteriosa:

- **GSAP e ScrollTrigger:** timelines, animações controladas por rolagem, títulos e sequências.
- **Three.js ou React Three Fiber:** objetos, materiais, iluminação e câmera tridimensionais.
- **Shaders:** distorções, máscaras, transições e efeitos de luz que sejam realmente úteis.
- **CSS e SVG:** microinterações e efeitos eficientes.
- **Lenis:** apenas se suavizar a navegação sem quebrar acessibilidade e scroll.

Oriente a duração inicial de títulos para 0,8–1,2 s e de microinterações para 150–350 ms, ajustando com bom senso. Use easing deliberado, princípios de antecipação, desaceleração, peso e continuidade. Evite repetir o mesmo fade-in em toda a página.

As animações de scroll devem corresponder à posição real do documento, inclusive em rolagens rápidas ou reversas. Não deixe timelines conflitarem entre si.

## 6. Aparência, materiais e iluminação

Selecione efeitos coerentes com o conceito:

- Film grain discreto, glow suave, parallax multicamada e profundidade.
- Reflexos, sombras, iluminação direcional e materiais metálicos/translúcidos.
- Máscaras geométricas, noise procedural e shader quando justificados.
- Câmeras, transformações espaciais e efeitos atmosféricos moderados.

Não use pós-processamento em excesso. Preferir acabamento e composição a muitos efeitos.

## 7. Interações funcionais

Implemente de verdade navegação, menus, controles 3D, seleção de variações, galeria, troca de conteúdo, estados e links. Todos os botões precisam ter comportamento verificável.

Não invente backend, autenticação, pagamento ou dados ao vivo inexistentes. Se uma integração for necessária e não puder ser concluída, descreva a dependência e ofereça fallback honesto.

## 8. Engenharia

Stack preferencial, ajustável às necessidades: React, TypeScript, Vite ou Next.js, Three.js, React Three Fiber, GSAP, CSS moderno e Lenis quando útil.

Separe componentes, cenas 3D, shaders, animações, hooks, materiais, serviços, estilos, recursos, configuração e testes. Mantenha componentes reutilizáveis, estado explícito, tratamento de erros e limpeza de recursos.

Evite listeners duplicados, loops de renderização desnecessários e vazamentos de memória. Descarte geometrias, texturas, materiais e animações quando não forem mais necessários.

## 9. Responsividade

Adapte a experiência a 1920×1080, 1366×768, 768×1024, 390×844 e aproximadamente 360 px de largura. Em mobile, recomponha enquadramento, tipografia, navegação e disposição — não apenas reduza tudo.

Simplifique cenas pesadas, mantenha interações por toque e preserve conteúdo essencial. Não dependa de hover como único meio de operar recursos.

## 10. Desempenho

Busque fluidez de aproximadamente 60 FPS em desktops compatíveis e boa experiência móvel, sem prometer resultados não medidos.

Utilize carregamento progressivo, imagens otimizadas, compressão de texturas, instancing quando pertinente, suspensões fora da viewport, controle de DPR e qualidade gráfica adaptativa. Crie fallback quando WebGL estiver indisponível.

## 11. Acessibilidade

Use HTML semântico, contraste adequado, estados de foco, suporte a teclado, descrições acessíveis, navegação compreensível e `prefers-reduced-motion`. Garanta acesso ao conteúdo mesmo sem efeitos de movimento ou 3D.

## 12. Recursos visuais

Empregue assets legítimos e coerentes. Se houver geração de imagens ou modelos, primeiro planeje sua função, depois crie e integre. Na ausência dessas ferramentas, utilize geometria procedural, SVG, composição fotográfica em camadas e CSS. Não apresente imagem estática como interação 3D real.

## 13. Fluxo obrigatório de execução

**Fase A — Pesquisa e conceito:** analise as informações disponíveis, escolha identidade original e estabeleça direção artística.

**Fase B — Direção de arte:** defina paleta em hex, fontes, materiais, iluminação, ritmo, navegação e sistema de design.

**Fase C — Storyboard:** descreva cada cena, estados inicial/final, câmera, trigger, transição, interação e adaptação móvel.

**Fase D — Implementação:** crie e integre código executável, cenas, componentes, estilos e funcionalidades. Não pare em um plano ou wireframe.

**Fase E — Validação:** execute build, verificação de tipos, testes funcionais, inspeção visual, console, responsividade, acessibilidade e desempenho quando possível.

**Fase F — Refinamento:** identifique e corrija problemas de composição, tipografia, profundidade, animações, bugs e performance.

## 14. Critérios de aceitação

A entrega deve apresentar:

1. Identidade visual original e coesa.
2. Abertura cinematográfica bem resolvida.
3. Múltiplas cenas conectadas com intenção.
4. Animações sincronizadas ao usuário.
5. Pelo menos uma interação visual avançada funcional.
6. Profundidade visual real ou cuidadosamente simulada.
7. Suporte a desktop e mobile.
8. Navegação acessível.
9. Suporte à redução de movimento.
10. Ausência de erros críticos conhecidos.
11. Build executado com sucesso, se houver ambiente de execução.
12. Instruções claras para rodar localmente.

Não declare critérios aprovados sem evidência.

## 15. Entregáveis

Forneça código-fonte, estrutura de arquivos, recursos gráficos, dependências, comandos de instalação/execução/build, explicação das funcionalidades, testes de fato realizados e limitações conhecidas.

Se possuir acesso ao ambiente, crie os arquivos diretamente. Caso não possa executar o projeto, deixe isso explícito e forneça a melhor implementação possível sem alegar testes inexistentes.

## 16. Princípio final

**Não construa apenas um site com animações. Construa uma experiência digital cinematográfica, original, utilizável e tecnicamente sólida.** Movimento, 3D, tipografia e transições devem servir à narrativa e ao conteúdo.

Comece pelo conceito e pelo storyboard; depois implemente, teste e refine a experiência sem interromper o trabalho após a primeira versão.
