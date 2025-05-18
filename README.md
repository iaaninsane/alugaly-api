
# 📘 Documento de Requisitos do Sistema  
**Projeto:** Plataforma Web de Aluguel de Itens entre Pessoas  
**Versão:** 1.0 (MVP)  
**Autor:** [Seu Nome]  
**Data:** [Data Atual]

---

## 📌 1. Visão Geral do Sistema

A plataforma tem como objetivo permitir que pessoas comuns disponibilizem seus bens pessoais para aluguel a outros usuários por tempo determinado. A ideia é promover a geração de renda extra por meio da economia compartilhada, com segurança e praticidade.

---

## ✅ 2. Requisitos Funcionais (RF)

- **RF01:** O sistema deve permitir que o usuário se cadastre e realize login com autenticação segura.
- **RF02:** O sistema deve permitir o cadastro de itens para aluguel, com dados como nome, descrição, fotos, valor por dia e localização.
- **RF03:** O sistema deve listar os itens disponíveis para aluguel, com filtros por categoria, localização e preço.
- **RF04:** O sistema deve permitir que um usuário solicite o aluguel de um item, informando o período desejado.
- **RF05:** O sistema deve permitir que o dono do item aprove ou rejeite solicitações de aluguel.
- **RF06:** O sistema deve registrar o histórico de aluguéis realizados e recebidos para cada usuário.
- **RF07:** O sistema deve permitir que usuários avaliem uns aos outros após a conclusão do aluguel.
- **RF08:** O sistema deve permitir envio de mensagens entre locador e locatário durante o aluguel.

---

## ⚙️ 3. Requisitos Não Funcionais (RNF)

- **RNF01:** O sistema deve ter interface web responsiva, compatível com dispositivos móveis.
- **RNF02:** O sistema deve garantir autenticação e autorização seguras, utilizando JWT.
- **RNF03:** O sistema deve armazenar os dados em banco de dados relacional (ex: PostgreSQL).
- **RNF04:** O sistema deve estar disponível online com uptime mínimo de 95% para MVP.
- **RNF05:** O sistema deve ser implementado com tecnologias open-source e baixo custo.

---

## ❌ 4. Requisitos Restritivos / Negativos

- **RR01:** O sistema **não deve permitir que um item alugado seja novamente disponibilizado por outra pessoa (subaluguel)**.
- **RR02:** O sistema **não deve permitir aluguéis com períodos sobrepostos a aluguéis já aprovados**.
- **RR03:** O sistema **não deve permitir que itens marcados como indisponíveis sejam alugados**.
- **RR04:** O sistema **não deve permitir que um usuário edite dados de outro usuário**.
- **RR05:** O sistema **não deve permitir solicitações de aluguel sem que o usuário esteja logado**.
- **RR06:** O sistema **não deve permitir a exclusão de um item com aluguel pendente ou ativo**.
- **RR07:** O sistema **não deve permitir alteração do valor diário do item durante um aluguel ativo**.
- **RR08:** O sistema **não deve permitir que o mesmo usuário envie múltiplas avaliações para o mesmo aluguel**.
- **RR09:** O sistema **não deve aprovar automaticamente solicitações de aluguel sem ação do dono do item**.
- **RR10:** O sistema **não deve permitir envio de mensagens com conteúdo ofensivo ou inadequado**.
