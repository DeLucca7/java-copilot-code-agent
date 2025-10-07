# 🚀 Guia Rápido de Templates de Issues

## 📌 Qual Template Usar?

Escolha o template baseado na sua necessidade:

| Situação | Template | Ícone |
|----------|----------|-------|
| Quero adicionar uma nova atividade | Adicionar Nova Atividade | 📝 |
| Preciso modificar horário/capacidade de uma atividade | Modificar Atividade Existente | ✏️ |
| Estudante não consegue se inscrever | Bug em Inscrição de Estudante | 🐛 |
| Não consigo fazer login | Problema de Autenticação | 🔐 |
| Filtros/listagem não funcionam | Bug Geral | 🐛 |
| Quero uma nova funcionalidade | Nova Funcionalidade | ✨ |
| Documentação está confusa/incompleta | Melhoria de Documentação | 📚 |

## 🎯 Exemplos de Uso Rápido

### ➕ Adicionar Nova Atividade
**Cenário:** Quero criar um "Clube de Fotografia"
1. Clique em "New Issue"
2. Escolha "📝 Adicionar Nova Atividade"
3. Preencha:
   - Nome: Clube de Fotografia
   - Descrição: Aprenda técnicas de fotografia...
   - Tipo: Artes
   - Dias: Tuesday, Thursday
   - Horário: 15:30 - 17:00
   - Capacidade: 20
4. Submeta a issue
5. Copilot implementa automaticamente!

### ✏️ Modificar Atividade
**Cenário:** Chess Club está lotado, preciso aumentar vagas
1. Clique em "New Issue"
2. Escolha "✏️ Modificar Atividade Existente"
3. Preencha:
   - Atividade: Chess Club
   - Tipo de modificação: Capacidade máxima
   - Nova capacidade: 30
   - Motivo: Alta demanda, fila de espera
4. Submeta a issue
5. Copilot ajusta automaticamente!

### 🐛 Bug de Inscrição
**Cenário:** Sistema aceita inscrições além do limite
1. Clique em "New Issue"
2. Escolha "🐛 Bug em Inscrição de Estudante"
3. Preencha:
   - Tipo: Validação incorreta (capacidade, duplicata, etc.)
   - Atividade: Drama Club
   - Descrição: Consegui inscrever 25 alunos mas limite é 20
   - Passos para reproduzir
   - Comportamento esperado vs atual
4. Submeta a issue
5. Copilot corrige o bug!

### 🔐 Problema de Login
**Cenário:** Não consigo fazer login
1. Clique em "New Issue"
2. Escolha "🔐 Problema de Autenticação"
3. Preencha:
   - Username: teacher.rodriguez
   - Tipo: Não consigo fazer login
   - Descrição detalhada do problema
   - Mensagem de erro (se houver)
   - Confirmação da senha
4. Submeta a issue
5. Copilot investiga e corrige!

### ✨ Nova Funcionalidade
**Cenário:** Quero exportar lista de participantes em Excel
1. Clique em "New Issue"
2. Escolha "✨ Nova Funcionalidade"
3. Preencha:
   - Categoria: Relatórios e Estatísticas
   - Título: Exportar lista de participantes
   - Problema/necessidade: Preciso enviar listas para administração
   - Solução proposta: Botão para baixar Excel
   - História de usuário
   - Critérios de aceitação
4. Submeta a issue
5. Copilot implementa!

## ✅ Dicas para Issues de Qualidade

### ✔️ Faça:
- ✅ Seja específico e detalhado
- ✅ Preencha TODOS os campos obrigatórios
- ✅ Use exemplos concretos
- ✅ Descreva o que você esperava vs o que aconteceu
- ✅ Inclua nomes exatos (atividades, usernames)
- ✅ Copie mensagens de erro completas

### ❌ Evite:
- ❌ Descrições vagas ("não funciona", "está errado")
- ❌ Deixar campos obrigatórios em branco
- ❌ Misturar múltiplos problemas em uma issue
- ❌ Usar nomes inventados (use nomes reais do sistema)
- ❌ Omitir passos para reproduzir

## 🤖 Como o Copilot Usa Suas Issues

Quando você cria uma issue com os templates:

1. **Copilot lê todos os campos** automaticamente
2. **Analisa o contexto** fornecido nas dicas de implementação
3. **Localiza os arquivos** corretos para modificar
4. **Implementa a solução** seguindo a arquitetura do projeto
5. **Adiciona testes** para garantir qualidade
6. **Valida a solução** executando testes
7. **Comita e faz push** das mudanças
8. **Atualiza a PR** com progresso

Tudo isso acontece **automaticamente** se você fornecer informações completas!

## 📊 Campos Mais Importantes

Para cada tipo de issue, estes são os campos CRÍTICOS:

### Adicionar Atividade
- ⭐ Nome (usado como ID único)
- ⭐ Dias da semana (formato correto)
- ⭐ Horários (formato HH:MM)
- ⭐ Capacidade máxima

### Modificar Atividade
- ⭐ Nome EXATO da atividade
- ⭐ Motivo da mudança
- ⭐ Novos valores (apenas os que mudam)

### Bug de Inscrição
- ⭐ Passos para reproduzir
- ⭐ Comportamento esperado vs atual
- ⭐ Mensagem de erro
- ⭐ Frequência

### Problema de Autenticação
- ⭐ Username exato
- ⭐ Descrição detalhada
- ⭐ Passos para reproduzir
- ⭐ Confirmação de senha

### Nova Funcionalidade
- ⭐ Problema/necessidade clara
- ⭐ Solução proposta
- ⭐ Critérios de aceitação
- ⭐ História de usuário

## 🎓 Glossário

**Issue:** Um pedido ou problema reportado no GitHub

**Template:** Formulário pré-estruturado para criar issues

**Copilot:** Agente de IA que implementa mudanças automaticamente

**PR (Pull Request):** Proposta de mudanças no código

**Commit:** Salvar mudanças no histórico do código

**Critérios de Aceitação:** Condições para considerar a issue completa

**Validação:** Verificação automática de dados

**Backend:** Parte do sistema que processa lógica e dados

**Frontend:** Interface visual que o usuário vê

**API:** Interface para comunicação entre partes do sistema

**Migration:** Script que configura dados iniciais do banco

## 📞 Precisa de Ajuda?

- **Documentação Completa:** `/docs/README.md`
- **Exemplos de Atividades:** Veja as atividades já cadastradas no sistema
- **Professores Padrão:** admin, teacher.rodriguez, teacher.chen
- **Discussões:** Use a aba "Discussions" no GitHub para dúvidas

---

**💡 Dica Final:** Quanto mais detalhes você fornecer, mais rápido e preciso será o trabalho do Copilot!
