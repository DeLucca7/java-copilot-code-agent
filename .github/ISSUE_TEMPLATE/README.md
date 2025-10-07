# 📋 Templates de Issues para Professores

Este diretório contém templates de issues padronizados para facilitar a comunicação de necessidades e problemas pelos professores da Mergington High School.

## 🎯 Objetivo

Os professores não se sentem confortáveis modificando o código diretamente e não têm certeza do que incluir nas issues. Estes templates garantem que todas as informações necessárias sejam coletadas para que o agente de codificação Copilot possa trabalhar de forma autônoma.

## 📝 Templates Disponíveis

### 1. 📝 Adicionar Nova Atividade (`adicionar-atividade.yml`)
**Quando usar:** Para solicitar a criação de uma nova atividade extracurricular no sistema.

**Informações coletadas:**
- Nome da atividade
- Descrição detalhada
- Tipo/categoria (Esportes, Artes, Acadêmico, Comunidade, Tecnologia)
- Dias da semana
- Horários de início e término
- Capacidade máxima de participantes
- Informações adicionais

**Exemplo de uso:** Criar uma nova atividade "Clube de Robótica" que ocorre às segundas e quartas das 15:30 às 17:00.

---

### 2. ✏️ Modificar Atividade Existente (`modificar-atividade.yml`)
**Quando usar:** Para alterar informações de uma atividade já cadastrada.

**Informações coletadas:**
- Nome da atividade a modificar
- Tipo de modificação (descrição, horário, capacidade, tipo)
- Novos valores para os campos a serem alterados
- Motivo da alteração
- Contexto adicional

**Exemplo de uso:** Aumentar a capacidade do "Chess Club" de 20 para 30 participantes devido ao aumento de demanda.

---

### 3. 🐛 Bug em Inscrição de Estudante (`bug-inscricao.yml`)
**Quando usar:** Para reportar problemas com inscrições ou cancelamentos de estudantes.

**Informações coletadas:**
- Tipo de problema (erro ao inscrever, erro ao cancelar, validação incorreta, etc.)
- Nome da atividade afetada
- Descrição detalhada do bug
- Passos para reproduzir
- Dados do professor e estudante envolvidos
- Mensagem de erro
- Frequência do problema
- Comportamento esperado vs. atual
- Impacto

**Exemplo de uso:** Reportar que o sistema aceita inscrições mesmo quando a atividade está cheia.

---

### 4. ✨ Nova Funcionalidade (`nova-funcionalidade.yml`)
**Quando usar:** Para propor uma nova funcionalidade para o sistema.

**Informações coletadas:**
- Categoria da funcionalidade
- Título e descrição
- Problema ou necessidade que resolve
- Solução proposta
- História de usuário
- Critérios de aceitação específicos
- Necessidade de mudanças na API
- Necessidade de mudanças no banco de dados
- Sugestões técnicas
- Mockup ou exemplo de interface
- Prioridade
- Alternativas consideradas

**Exemplo de uso:** Solicitar funcionalidade para exportar lista de participantes em formato CSV.

---

### 5. 🔐 Problema de Autenticação (`problema-autenticacao.yml`)
**Quando usar:** Para reportar problemas com login, logout ou autenticação de professores.

**Informações coletadas:**
- Tipo de problema (não consigo fazer login, sessão expira, senha não aceita, etc.)
- Nome de usuário do professor
- Role do usuário (TEACHER ou ADMIN)
- Descrição detalhada
- Passos para reproduzir
- Mensagem de erro
- Quando o problema ocorre
- Navegador utilizado
- Confirmação da senha
- Comportamento esperado vs. atual
- Se afeta outros usuários
- Solução temporária (se houver)

**Exemplo de uso:** Reportar que o login não funciona mesmo com senha correta.

---

### 6. 🐛 Bug Geral (`bug-geral.yml`)
**Quando usar:** Para reportar outros bugs não relacionados a inscrição ou autenticação.

**Informações coletadas:**
- Área do sistema afetada
- Resumo do bug
- Descrição detalhada
- Passos para reproduzir
- Comportamento esperado vs. atual
- Mensagens de erro ou logs
- Severidade
- Frequência
- Ambiente
- Contexto de dados
- Screenshots ou evidências
- Solução temporária

**Exemplo de uso:** Reportar que o filtro por dia da semana não funciona corretamente.

---

### 7. 📚 Melhoria de Documentação (`melhoria-documentacao.yml`)
**Quando usar:** Para solicitar melhorias, correções ou adições à documentação.

**Informações coletadas:**
- Tipo de melhoria (adicionar, corrigir, clarificar, exemplos, etc.)
- Área da documentação
- Arquivo ou seção específica
- Problema atual
- Melhoria proposta
- Impacto para usuários
- Conteúdo sugerido
- Prioridade

**Exemplo de uso:** Solicitar instruções mais claras sobre como adicionar novas atividades.

---

## 📋 Estrutura dos Templates

Todos os templates seguem uma estrutura consistente com:

### ✅ Critérios de Aceitação
Lista clara de quando a issue é considerada completa. Inclui verificações como:
- Funcionalidade implementada corretamente
- Testes passando
- Documentação atualizada
- Sem regressões

### 🔧 Dicas de Implementação
Instruções específicas para o agente Copilot, incluindo:
- Arquivos relevantes a modificar
- Padrões e convenções a seguir
- Checklist de verificações
- Exemplos de código
- Referências à arquitetura

### 📋 Contexto Adicional
Informações sobre:
- Estrutura do projeto
- Padrões arquiteturais
- Limitações técnicas
- Dependências

## 🤖 Para o Agente Copilot

Quando trabalhar com issues criadas por estes templates:

1. **Leia todos os campos** - Os templates coletam todas as informações necessárias
2. **Siga os critérios de aceitação** - Use-os como checklist de conclusão
3. **Use as dicas de implementação** - Elas apontam para os arquivos e padrões corretos
4. **Mantenha a arquitetura** - Respeite Clean Architecture e separação de camadas
5. **Adicione testes** - Sempre que possível, adicione testes para prevenir regressão
6. **Valide sua solução** - Execute os testes e valide manualmente quando aplicável

## 🔗 Recursos Relacionados

- **Documentação do Sistema:** `/docs/README.md`
- **Instruções Copilot:** `/.github/copilot-instructions.md`
- **README Principal:** `/README.md`

## 🛠️ Configuração

O arquivo `config.yml` configura o comportamento dos issue templates:
- Desabilita issues em branco (força uso dos templates)
- Fornece links para documentação e discussões
- Garante que todas as issues tenham informações completas

---

**Nota para Professores:** Sempre que precisar de uma mudança no sistema, escolha o template apropriado ao criar uma nova issue. Os templates garantem que você forneça todas as informações necessárias para que as mudanças sejam implementadas rapidamente.
