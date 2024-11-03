# Guia de Contribuição

Obrigado por considerar contribuir para este projeto! Para mantermos um fluxo de trabalho organizado e consistente, por favor, siga as diretrizes abaixo ao criar issues, commits, pull requests, branches e comentários no código.

## Sumário

- [Issues](#issues)
- [Commits](#commits)
- [Pull Requests](#pull-requests)
- [Estrutura de Branches](#estrutura-de-branches)
- [Comentários no Código](#comentários-no-código)

## Issues

### Criação de Issues

- **Título**: Deve ser claro e conciso, resumindo o problema ou a sugestão.
- **Descrição**: Forneça detalhes completos, incluindo passos para reproduzir (se aplicável), contexto e qualquer informação relevante.

### Uso de Templates

Utilize os templates específicos para cada tipo de issue:

- **Bug Report**: Para reportar erros ou falhas.
- **Feature Request**: Para sugerir novas funcionalidades.
- **Task**: Para tarefas gerais que não se enquadram nos demais tipos.

## Commits

### Formato dos Commits

Siga o padrão:

```
<tipo>: <descrição breve>
```

### Tipos de Commits

- **feat**: Adição de uma nova funcionalidade.
- **fix**: Correção de um bug.
- **docs**: Alterações na documentação.
- **style**: Alterações de formatação ou estilo que não afetam a lógica do código.
- **refactor**: Alterações que melhoram o código sem adicionar funcionalidades ou corrigir bugs.
- **test**: Adição ou correção de testes.
- **chore**: Atualizações de tarefas de build ou ferramentas auxiliares.

### Exemplos

- `feat: adicionar validação de email no formulário de cadastro`
- `fix: corrigir erro de null pointer no módulo de autenticação`

## Pull Requests

### Estrutura de Pull Requests para Código

- **Título**: Use o mesmo padrão dos commits.
- **Descrição**:
  - **O que foi feito**: Descreva as mudanças realizadas.
  - **Por que foi feito**: Explique a motivação por trás das mudanças.
  - **Como testar**: Instruções para testar as alterações.

### Estrutura de Pull Requests para Documentos

- **Título**: Descreva claramente o conteúdo adicionado ou modificado.
- **Descrição**:
  - **Resumo**: Breve descrição das mudanças.
  - **Referências**: Links ou referências relacionadas.

## Estrutura de Branches

Use o seguinte padrão para nomear branches:

```
<numero_da_issue>-<descricao-kebab-case>
```

### Exemplo

- Para a issue **#3 Cria documento de BPMN**:

  ```
  3-cria-documento-de-bpmn
  ```

## Comentários no Código

### Boas Práticas

- **Clareza**: Os comentários devem esclarecer partes do código que não são imediatamente óbvias.
- **Relevância**: Evite comentários óbvios ou redundantes.
- **Atualização**: Mantenha os comentários atualizados com as mudanças no código.

### Padronização

- **Funções e Classes**: Utilize docstrings ou comentários estruturados para documentar a finalidade, parâmetros e retorno.
- **TODOs**: Marque com `// TODO:` seguido da tarefa a ser realizada.

### Exemplo

```javascript
/**
 * Calcula a soma de dois números.
 *
 * @param {number} a - O primeiro número.
 * @param {number} b - O segundo número.
 * @returns {number} A soma de `a` e `b`.
 */
function soma(a, b) {
  return a + b;
}
```