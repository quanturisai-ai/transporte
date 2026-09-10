# Plano de Implementação — Funcionalidades da Versão Antiga

Este documento lista, de forma numerada, as funcionalidades identificadas na
versão antiga (`index_antigo.html`) que ainda não existem na versão nova
(`index.html`), com base no diagnóstico comparativo realizado em 2026-09-10.

A ideia é trazer apenas a **funcionalidade** (comportamento), reimplementada
seguindo o padrão visual e a organização de código já estabelecidos na versão
nova — não o código da versão antiga.

Status possíveis: `Pendente`, `Em andamento`, `Concluído`.

## Login / Autenticação

1. **Cadastro de motorista eventual/diarista** — opção no login para cadastrar
   um motorista avulso (nome + CPF) sem precisar editar o código.
   Status: Pendente

## Painel do Motorista

2. **Vistoria de avarias no início do turno** — checkbox "possui avaria
   prévia?" com tipo de dano, descrição e foto.
   Status: Pendente
3. **Tipo de combustível no abastecimento** — seleção de Diesel S10 /
   Gasolina / Etanol, além do valor e litros já existentes.
   Status: Pendente
4. **Notificação individual ao paciente via WhatsApp** — botão no card do
   paciente que abre o WhatsApp com mensagem avisando que o veículo iniciou
   o deslocamento.
   Status: Concluído
5. **Disparo em massa "Iniciar Rota Geral"** — marca todas as viagens do dia
   do motorista como em trânsito de uma vez e notifica o primeiro paciente
   da lista via WhatsApp.
   Status: Concluído
6. **Rota multi-parada no Google Maps** — monta uma URL do Google Maps com
   todos os destinos do dia, na ordem dos horários.
   Status: Concluído
7. **Alerta preventivo de manutenção por e-mail** — abre um e-mail (mailto)
   pré-preenchido para o setor de frotas.
   Status: Pendente
8. **Despertador/alarme de horário** — lembrete simples de horário dentro do
   app.
   Status: Pendente
9. **Lançamento de manutenção pelo próprio motorista** — hoje só a
   Gestão/Admin registra manutenção; motorista não lança e isso não
   alimenta a meta de km do veículo.
   Status: Pendente
10. **Scanner de documentos médicos** — digitalizar guia de encaminhamento,
    laudo, prontuário de ambulância etc. (hoje só existe foto do comprovante
    de embarque).
    Status: Pendente
11. **Diário de bordo por data (calendário)** — consultar boletins de dias
    passados e registrar "dia sem viagem" com motivo.
    Status: Pendente
12. **Sincronizar com planilha (nuvem)** — ação distinta do download local
    de CSV que já existe hoje.
    Status: Pendente

## Painel de Gestão / Admin

13. **Painel de ocorrências e avarias reportadas** — depende do item 2
    (vistoria de avarias) para ter dados a exibir.
    Status: Pendente
14. **Relatório "Vistoria Inicial & Avarias"** — novo tipo de relatório
    exportável no gerador de relatórios da Gestão.
    Status: Pendente

---

## Histórico de atualizações

- 2026-09-10: Documento criado com o diagnóstico completo.
- 2026-09-10: Itens 4, 5 e 6 (WhatsApp e rotas) implementados.
