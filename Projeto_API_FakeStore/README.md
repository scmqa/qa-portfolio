# Teste de API – Fake Store API

## Objetivo

Avaliar o comportamento funcional da Fake Store API, verificando endpoints relacionados à consulta de produtos e autenticação de usuários. O teste teve como foco a validação das respostas HTTP, estrutura dos dados retornados e tratamento de erros.

---

## Escopo do Teste

Foram avaliados os seguintes cenários:

- Listagem de produtos
- Consulta de produto específico
- Consulta de produto inexistente
- Autenticação com credenciais válidas
- Autenticação com credenciais inválidas

---

## Ambiente de Teste

Ferramenta: Postman  
Sistema Operacional: Windows 10 Pro  
Formato de resposta: JSON  

Base URL utilizada:

https://fakestoreapi.com

---

## Casos de Teste Executados

| ID | Cenário |
|----|--------|
| TC-API-001 | Listar produtos |
| TC-API-002 | Buscar produto específico |
| TC-API-003 | Consulta de produto inexistente |
| TC-API-004 | Login com credenciais válidas |
| TC-API-005 | Login com credenciais inválidas |

---

## Principais Resultados

Durante os testes foi possível observar que:

- A API retorna corretamente a lista de produtos.
- A consulta de produto específico retorna os dados esperados.
- Consultas a recursos inexistentes retornam resposta vazia com status 200.
- A autenticação com credenciais válidas retorna token de acesso.
- Credenciais inválidas retornam erro 401 Unauthorized.

---

## Conclusão

Os endpoints avaliados apresentaram comportamento consistente com os cenários testados, retornando respostas HTTP adequadas e dados válidos em formato JSON. Foi registrada uma observação no comportamento da consulta de produtos inexistentes, que retorna status 200 com resposta vazia.

---

## Relatório Completo

O relatório detalhado da execução dos testes pode ser encontrado no arquivo:

**Relatorio_Teste_API_FakeStore_2026-03-15.pdf**
