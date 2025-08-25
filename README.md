# Casos de Teste Manuais: Gherkin, Checklist e Passo a Passo

Este repositório reúne exemplos práticos de casos de teste manuais, organizados em três formatos principais para apoiar a garantia de qualidade em projetos de software.

---

## 📋 Checklist

Checklist é uma abordagem simples e objetiva para validar funcionalidades, fluxos ou requisitos. Ideal para cenários onde a cobertura rápida é essencial.

**Exemplo:**
- [ ] Usuário consegue acessar a tela de login
- [ ] Campo de senha aceita caracteres especiais
- [ ] Mensagem de erro exibida para credenciais inválidas
- [ ] Botão "Entrar" desabilitado até preencher todos os campos

---

## 📝 Step by Step

Step by Step detalha cada ação do usuário e o resultado esperado, facilitando a execução e rastreabilidade dos testes.

**Exemplo:**
1. Acesse o sistema pela URL principal
2. Informe usuário e senha válidos
3. Clique no botão "Entrar"
4. Verifique se o dashboard é exibido corretamente
5. Valide se o nome do usuário aparece no topo da tela

---

## 🦋 Gherkin (BDD)

Gherkin é uma linguagem estruturada para descrever cenários de teste de forma colaborativa, seguindo o padrão Given/When/Then.

**Exemplo:**
```gherkin
Funcionalidade: Login do usuário
  Como um usuário do sistema
  Quero acessar minha conta
  Para utilizar as funcionalidades disponíveis

Cenário: Login com credenciais válidas
  Dado que estou na página de login
  Quando informo usuário e senha válidos
  E clico em "Entrar"
  Então devo visualizar o dashboard
  E meu nome deve aparecer no topo da tela
```

---

## 📁 Estrutura Sugerida

- `/checklists/` — Exemplos de checklists por funcionalidade
- `/passo-a-passo/` — Casos de teste detalhados
- `/gherkin/` — Cenários escritos em Gherkin

---

## 💡 Recomendações
- Use Checklist para validações rápidas e rotineiras
- Utilize Step by Step para testes detalhados e rastreáveis
- Adote Gherkin para colaboração entre QA, PO e devs, e para automação BDD

---

> Sinta-se à vontade para contribuir com novos exemplos ou adaptar os modelos conforme a necessidade do seu projeto!
