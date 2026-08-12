# 📋 Casos de Teste

Casos de teste desenvolvidos como parte do portfólio prático de QA, com foco em testes funcionais manuais, elaboração, execução e documentação dos resultados.

## CT-001 — Login com Credenciais Válidas

> Caso de teste documentado e executado no Zephyr (SmartBear), integrado ao Jira.

### Informações do Caso

| Campo | Descrição |
|---|---|
| **ID** | CT-001 (SCRUM-T1) |
| **Título** | Validar login com credenciais válidas |
| **Módulo** | Autenticação |
| **Tipo de Teste** | Funcional |
| **Prioridade** | Alta |
| **Ambiente** | [The Internet - Login](https://the-internet.herokuapp.com/login) |
| **Pré-condições** | Usuário de teste disponibilizado pelo ambiente e navegador atualizado (Chrome ou Firefox). |

### Dados da Execução

| Campo | Valor |
|---|---|
| **Ciclo de Execução** | SCRUM-R1 |
| **Execução** | SCRUM-E1 |
| **Status da Execução** | ✅ Pass |
| **Status do Caso** | ✅ Approved |
| **Executado por** | Vinicios Rodrigues da Silva |
| **Data** | 29/07/2026 |

### Passos Executados

| # | Passo | Dados de Teste | Resultado Esperado | Resultado Obtido |
|---|---|---|---|---|
| 1 | Acessar a página de login | [The Internet - Login](https://the-internet.herokuapp.com/login) | Página carregada corretamente | ✅ Conforme esperado |
| 2 | Informar usuário válido | `tomsmith` | Campo preenchido sem erros | ✅ Conforme esperado |
| 3 | Informar senha válida | `SuperSecretPassword!` | Campo preenchido com caracteres mascarados | ✅ Conforme esperado |
| 4 | Clicar em **Login** | — | Usuário autenticado e redirecionado para a área segura com a mensagem **"You logged into a secure area!"** | ✅ Conforme esperado |

### Resultado

**PASSOU ✅**

O usuário conseguiu realizar o login utilizando credenciais válidas e foi redirecionado corretamente para a área segura.

### Evidências

As evidências da execução estão disponíveis na pasta [`evidencias`](../evidências/).

- CT-001 — Acesso à página de login
- CT-001 — Preenchimento dos dados
- CT-001 — Execução do teste
- CT-001 — Login realizado com sucesso
