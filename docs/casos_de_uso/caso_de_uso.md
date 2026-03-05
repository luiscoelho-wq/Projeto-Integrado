# Casos de Uso — Atlas Contábil

Documento contendo os principais casos de uso do aplicativo **Atlas Contábil**, desenvolvido como projeto integrado do módulo **Desenvolvimento de Sistemas Móveis**.

---

## Caso de Uso 01 — Realizar Login

**Ator:** Usuário (Contador)  
**Objetivo:** Acessar o aplicativo mediante autenticação válida.

### Pré-condições:
- O aplicativo deve estar instalado e funcional.
- O usuário deve possuir acesso autorizado ao sistema acadêmico.

### Pós-condições:
- Sessão iniciada com sucesso.
- Usuário redirecionado ao Dashboard.

### Fluxo Principal:
1) Usuário abre o aplicativo.
2) Sistema exibe a tela de login.
3) Usuário informa credenciais.
4) Sistema valida os dados inseridos.
5) Sistema redireciona para a tela inicial (Dashboard).

### Fluxos Alternativos:

**A1 — Credenciais inválidas**
1) Sistema identifica erro nas credenciais.
2) Exibe mensagem informando falha no login.
3) Permite nova tentativa.

**A2 — Campos não preenchidos**
1) Sistema detecta campos vazios.
2) Solicita preenchimento obrigatório.

### Regras de Negócio:
- RN01: O acesso ao sistema é restrito a usuários autorizados.
- RN02: Dados utilizados são apenas simulados para fins acadêmicos.

### Requisitos Relacionados:
- RF01 — Exibição da tela inicial
- RF03 — Navegação entre telas
- RNF01 — Usabilidade
- RNF11 — Confiabilidade básica

---

## Caso de Uso 02 — Realizar Pesquisa Informativa

**Ator:** Usuário (Contador)  
**Objetivo:** Consultar orientações contábeis simuladas por meio da pesquisa inteligente.

### Pré-condições:
- Usuário autenticado no sistema.
- Tela principal carregada.

### Pós-condições:
- Resultado informativo exibido ao usuário.

### Fluxo Principal:
1) Usuário acessa a funcionalidade de pesquisa.
2) Digita uma consulta na barra de busca.
3) Sistema processa a solicitação.
4) Sistema apresenta orientações técnicas simuladas.

### Fluxos Alternativos:

**A1 — Pesquisa vazia**
1) Sistema identifica ausência de texto.
2) Solicita inserção de termo de pesquisa.

**A2 — Nenhum resultado encontrado**
1) Sistema informa ausência de resultados.
2) Sugere nova pesquisa.

### Regras de Negócio:
- RN02: Informações exibidas possuem caráter educacional.
- RN03: Resultados não representam aconselhamento profissional real.

### Requisitos Relacionados:
- RF04 — Pesquisa informativa
- RF05 — Exibição de resultados da pesquisa
- RNF03 — Desempenho
- RNF07 — Segurança acadêmica

---

## Caso de Uso 03 — Simular Cenário Tributário

**Ator:** Usuário (Contador)  
**Objetivo:** Avaliar impactos estratégicos simulados a partir da alteração de parâmetros tributários.

### Pré-condições:
- Usuário autenticado.
- Acesso ao módulo de simulação.

### Pós-condições:
- Cenário estratégico atualizado e exibido.

### Fluxo Principal:
1) Usuário acessa o simulador estratégico.
2) Altera parâmetros simulados (faturamento, regime ou funcionários).
3) Sistema processa os dados.
4) Sistema apresenta resultado estimado do cenário.

### Fluxos Alternativos:

**A1 — Valores inválidos**
1) Sistema identifica dados inconsistentes.
2) Solicita correção antes da simulação.

**A2 — Cancelamento da simulação**
1) Usuário retorna à tela anterior.
2) Nenhuma alteração é salva.

### Regras de Negócio:
- RN04: Simulações utilizam apenas dados fictícios.
- RN05: Resultados possuem finalidade exclusivamente acadêmica.

### Requisitos Relacionados:
- RF08 — Simulação básica de cenário tributário
- RF11 — Atualização visual das informações
- RNF05 — Manutenibilidade
- RNF12 — Clareza de escopo

---
