Test Report 1: Valid Login with Correct Credentials ✅
Title: Valid Login with Correct Credentials
Description:
Teste de autenticação básica no SuiteCRM com credenciais válidas.

Objective:
Verificar se o sistema:

Aceita credenciais válidas

Redireciona corretamente para o dashboard

Inicia a sessão sem erros

Test Environment (Único utilizado em todos os testes):
Sistema Operacional: Windows 10 Pro (Build 19045)

Navegador: Google Chrome Versão 115.0.5790.110 (64-bit)

Resolução: 1920x1080 (Full HD)

Conectividade: Cabo de rede (Ethernet)

Hardware: Intel Core i5-10ª geração, 16GB RAM

Test Procedure:
Acessei https://crm.alunostds.dev.br

Inseri:

Username: "admin"

Password: "admin123"

Cliquei no botão "Login"

Monitorei:

Tempo de resposta

Redirecionamento

Mensagens de erro

Console do navegador

Expected Result:
Autenticação em ≤2 segundos

Redirecionamento para /#/dashboard

Carregamento completo em ≤3 segundos

Nenhum erro no console

Actual Result:
✅ Sucesso Total

Tempo de autenticação: 1.2s

Redirecionamento correto para dashboard

Load completo: 2.8s

Console limpo (0 errors)

Evidence:
PrintScreen_Login_20240515.png

Timestamp: 15/05/2024 14:30:22

Campos preenchidos visíveis

PrintScreen_Dashboard_20240515.png

Timestamp: 15/05/2024 14:30:24

Widgets carregados: Calendar, Tasks, Leads

Observações:
Todos os testes subsequentes foram realizados no MESMO AMBIENTE (Windows 10/Chrome 115)

Não foram realizados testes cross-browser ou multi-OS

O ambiente de teste foi reiniciado antes da execução

Notas Técnicas:
O Windows estava com todas as atualizações instaladas

Chrome em modo limpo (sem extensões)

Cache limpo antes do teste

Teste realizado em horário comercial (14:30h)
