# ***Mapa Mental***

## <a>1. Introdução</a>

No Design Sprint da equipe ficou decidido que cada integrante deveria elaborar um Rich Picture acerca do tema escolhido para o projeto (Plataforma de estudos para o ENEM), na reunião de [30/10/2024](/Atas/reuniao_30-10-24.md) todos os Rich Pictures foram apresentados e discutidos o que resultou na elaboração do mapa mental.

## <a>2. Rich Pictures da Equipe</a>

<div style="position: relative; width: 100%; height: 0; padding-top: 100.0000%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https://www.canva.com/design/DAGVP0l7fCs/9RGEnxOn8Vl-DUPB5qvh3g/view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAGVP0l7fCs&#x2F;9RGEnxOn8Vl-DUPB5qvh3g&#x2F;view?utm_content=DAGVP0l7fCs&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">Rich Pictures</a>

_Fonte: [Gustavo Melo](https://github.com/gusrberto) e [Eric Silveira](https://github.com/ericbky)_

## <a>3. Mapa Mental</a>

<div style="position: relative; width: 100%; height: 0; padding-top: 100.0000%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https://www.canva.com/design/DAGVP8c_ZmE/nkBOvVYTpRMKnNvkPXNbtA/view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAGVP8c_ZmE&#x2F;nkBOvVYTpRMKnNvkPXNbtA&#x2F;view?utm_content=DAGVP8c_ZmE&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">Mapa Mental</a>

_Fonte: [Gustavo Melo](https://github.com/gusrberto) e [Eric Silveira](https://github.com/ericbky)_

## <a>4. Pontos Importantes</a>

A plataforma de estudos visa fornecer uma experiência personalizada, motivadora e interativa para seus usuários, através de funcionalidades que integram dados de desempenho, interesses individuais e disponibilidade de tempo. Este documento detalha as principais funcionalidades propostas para tornar a experiência mais eficaz e engajante.

#### <a>Visão Geral da Arquitetura Técnica</a>

| Funcionalidade | Descrição |
|----------------|-----------|
| **Cadastro** | Estudantes e professores podem se cadastrar e configurar perfis. Estudantes ganham emblemas por metas e realizam um pré-simulado inicial. Professores podem submeter resoluções e materiais. |
| **Questões** | Fórum de dúvidas para alunos e professores, com notificações e suporte a questões do ENEM. |
| **Simulados** | Simulados cronometrados, com foco em conteúdos específicos ou completos, e análise de resultados ao final. |
| **Materiais/Trilhas de Estudo** | Professores aprovados compartilham materiais e trilhas de estudo que os alunos podem acompanhar. |
| **Cronograma de Estudos** | Cronograma baseado no desempenho, interesse e tempo disponível do estudante. |
| **Dashboard** | Interface com gráficos de progresso e metas personalizáveis para acompanhar o desempenho. |
| **Ranking e Conquistas** | Ranking por desempenho e conquistas para motivar e engajar usuários. |
| **Padronização de Conteúdo** | Nomenclatura e organização padronizadas para consistência e precisão nas métricas. |

_Fonte: [Gustavo Melo](https://github.com/gusrberto) e [Eric Silveira](https://github.com/ericbky)_

### <a>4.1. Cadastro</a>

* O Estudante pode se cadastrar na plataforma assim tendo acesso ao seu perfil onde consegue editar sua foto e bio, além de poder visualizar o perfil de outros estudantes na plataforma (O aluno tem opção de privar o perfil ou deixá-lo público).
* Caso o estudante alcance certas metas na plataforma ele pode ganhar emblemas/insígnias que aparecerão no seu perfil.
* Logo após o cadastro o estudante é submetido a um pré-simulado para que a plataforma possa entender seus pontos fortes e fracos, a estudante também pode manualmente escolher em quais conteúdos ele deseja focar.
* Professores também podem se cadastrar na plataforma, se tornando um professor verificado com a apresentação de seu currículo para a administração do site.
* Sendo um professor verificado é possível cadastrar resoluções detalhadas de questões, cadastrar materiais de estudos e participar como "moderador" nos fóruns de dúvidas verificando a integridade das respostas.

### <a>4.2. Questões</a>

* Fórum de dúvidas onde os alunos podem cadastrar perguntas sobre as questões presentes na plataforma para outros alunos ou professores responderem, além do autor da pergunta no fórum receber uma notificação ao ser respondido.
* Questões avulsas do ENEM podem ser respondidas na plataforma, podendo ser selecionadas através de um filtro de pesquisa.

### <a>4.3. Simulados</a>

* Caso o estudante queira responder a um simulado ele pode escolher entre: um simulado focado apenas em certos conteúdos que ele deseja praticar ou um simulado completo com distribuição de conteúdos semelhante ao ENEM, sendo que o primeiro não conta para ranking do site.
* Os simulados serão cronometrados para gerar uma experiência semelhante à prova real.
* Ao final do simulado o aluno tem acesso ao gabarito, além disso é feito uma análise de resultado onde se aumenta a probabilidade de questões que o estudante errou aparecerem em simulados futuros.

### <a>4.4. Materiais/Trilhas de Estudo</a>

* O professor verificado poderá submeter materiais de estudos como vídeos, apostilas, PDFs para os alunos estudarem, desde que sejam aprovados pelos moderadores.
* Em cima dos conteúdos disponíveis o professor pode cadastrar uma trilha de estudo (semelhante ao Duolingo) na qual os alunos podem fazer e marcar seu progresso.

### <a>4.5. Cronograma de Estudos Personalizado

O cronograma de estudos será gerado a partir de métricas detalhadas de:
- **Desempenho:** Considera a taxa de acertos e o progresso em diferentes áreas do conhecimento, permitindo que o cronograma priorize tópicos onde o usuário precisa de maior atenção.
- **Interesse:** Baseia-se nas preferências de áreas e temas definidos pelos usuários, ajustando o cronograma para incluir temas de interesse com maior frequência.
- **Disponibilidade:** O cronograma também é adaptável ao tempo disponível do usuário, distribuindo os conteúdos de maneira que possam ser estudados de forma eficaz dentro da janela de tempo declarada.

Essa personalização busca otimizar o aprendizado ao mesmo tempo que respeita as limitações e preferências do usuário, proporcionando uma jornada de estudos estruturada e focada.

### <a>4.6. Dashboard de Progresso e Aproveitamento</a>

O dashboard é a interface principal onde o usuário visualiza o progresso dos estudos e o desempenho em tempo real. Ele oferece:
- **Insights de Progresso:** Gráficos detalhados que indicam o avanço nos temas estudados, incluindo tempo de estudo, quantidade de questões resolvidas, e taxa de conclusão de atividades.
- **Métricas de Aproveitamento:** Exibe a acurácia e o desempenho do usuário por tópico, permitindo uma análise da curva de aprendizado e sugerindo áreas de melhoria.
- **Interatividade:** A interface permite que o usuário configure metas e receba feedbacks em tempo real, aumentando o engajamento.

### <a>4.7 Ranking de Usuários e Conquistas</a>

#### <a>Ranking de Usuários</a>

Para motivar e engajar os usuários, será implementado um sistema de ranking:
- **Rankings por Simulado:** Em cada simulado, um ranking dos melhores desempenhos será exibido, aumentando a competitividade e incentivando o desempenho.
- **Perfis Públicos e Conexões:** Os usuários poderão seguir uns aos outros e acompanhar o progresso em seus perfis, promovendo uma comunidade de estudo colaborativa.

#### <a>Conquistas e Emblemas</a>

Além do ranking, os usuários poderão desbloquear conquistas que incentivam o estudo contínuo e atingimento de metas, como:
- **Metas Pessoais:** Contabilização de dias consecutivos de estudo e metas de questões diárias.
- **Ganhos de Experiência (XP):** Sistema de XP recompensando o cumprimento de objetivos, como resolver uma quantidade mínima de questões por dia ou completar todos os tópicos de um módulo.

Esses elementos de gamificação tornam o estudo mais atrativo e ajudam a manter o usuário engajado a longo prazo.

### <a>4.8. Padronização de Conteúdo e Metodologias</a>

Para garantir a qualidade e consistência do conteúdo na plataforma, será adotada uma padronização que abrange:
- **Nomenclatura Consistente:** Uniformização das técnicas de estudo e terminologia usada para organizar as questões, facilitando a análise de dados e o agrupamento temático.
- **Restrições de Seleção de Conteúdo:** Implementação de filtros para evitar duplicação ou escolha inconsistente de conteúdos, promovendo clareza nos bancos de questões e nas métricas de desempenho.

Essas medidas não apenas melhoram a experiência do usuário, mas também otimizam a precisão das análises de dados e a relevância dos relatórios gerados pela plataforma.

---

## <a>Histórico de Versão</a>

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ---------- |
| `1.0`  | 01/11/2024 | Criação do documento do Mapa Mental  | [Gustavo Melo](https://github.com/gusrberto)  | [Eric Silveira](https://github.com/ericbky)  |
| `1.1`  | 02/11/2024 | Inserção de tópicos importantes do Mapa mental  | [Eric Silveira](https://github.com/ericbky)  | [Gustavo Melo](https://github.com/gusrberto)  |