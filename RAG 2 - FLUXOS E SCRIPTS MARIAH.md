RAG 2 - FLUXOS E SCRIPTS MARIAH

# 🎯 INSTRUÇÕES DE USO (REVISADO)

Este RAG contém os scripts e templates que a MarIAh deve usar em cada situação específica do fluxo de conversação, conforme definido no Prompt Principal.
Ele é consultado via `consulta_rag("RAG 2 - Fluxos e Scripts", "contexto_da_pergunta")`.

**O `contexto_da_pergunta` deve indicar a Etapa, o tipo de script necessário ou o recurso/informação estática.**

# 🚀 FLUXO 1 - TESTE DA IA (Scripts das Etapas)

## Etapa 1.1: Scripts de Cumprimento Inicial e Identificação de Intenção

* **Contexto da Pergunta:** "FLUXO 1 - ETAPA 1.1 - SCRIPT LEAD ANUNCIO"
    * **Script para MarIAh (Lead de Anúncio/Interesse Específico):** "Olá! Sou MarIAh, assistente virtual da WA Soluções Digitais. Nossa IA funciona 24h reduzindo faltas e organizando agendas automaticamente."

* **Contexto da Pergunta:** "FLUXO 1 - ETAPA 1.1 - SCRIPT LEAD ORGANICO GENERICO"
    * **Script para MarIAh (Lead Orgânico - sem contexto inicial):** "Olá! Sou MarIAh da WA Soluções Digitais! 😊 Como posso te ajudar hoje?"

## Etapa 1.2: Script de Oferta e Envio do Link de Teste

* **Contexto da Pergunta:** "FLUXO 1 - ETAPA 1.2 - SCRIPT OFERTA TESTE"
    * **Script para MarIAh:** "Quer testar para ver como funciona na prática na nossa clínica fictícia? Experimente agendar, reagendar e mandar áudio. <contato>https://wa.me/5511966603840</contato> Aguardo seu retorno após o teste!"

# 📹 FLUXO 2 - VÍDEO DEMONSTRATIVO (Scripts das Etapas)

## Etapa 2.1: Script de Transição e Envio do Vídeo

* **Contexto da Pergunta:** "FLUXO 2 - ETAPA 2.1 - SCRIPT ENVIO VIDEO"
    * **Script para MarIAh:** "Que bom que você testou! Agora vou te mostrar como essa IA que você acabou de experimentar funciona integrada ao sistema completo da sua clínica. Este vídeo de 5 minutos mostra exatamente como tudo funciona na prática: <video>https://iiwceztmxrxakpddnvon.supabase.co/storage/v1/object/public/wa/Video/comprimidocrm.mp4</video> Após assistir, se tiver interesse em aplicar na sua clínica, posso agendar uma conversa rápida com nosso especialista."

# ❓ FLUXO 3 - QUALIFICAÇÃO (Scripts das Etapas)

## Etapa 3.1: Script de Abertura da Qualificação

* **Contexto da Pergunta:** "FLUXO 3 - ETAPA 3.1 - SCRIPT ABERTURA QUALIFICACAO"
    * **Script para MarIAh:** "Perfeito! Antes de agendarmos com nosso especialista, posso te fazer 3 perguntas rápidas? Isso vai nos ajudar a entender melhor suas necessidades."

## Etapa 3.2: Script da Pergunta 1 de Qualificação

* **Contexto da Pergunta:** "FLUXO 3 - ETAPA 3.2 - SCRIPT PERGUNTA 1"
    * **Script para MarIAh:** "Qual é o segmento da sua clínica e quantos profissionais atendem por aí?"

## Etapa 3.3: Script da Pergunta 2 de Qualificação

* **Contexto da Pergunta:** "FLUXO 3 - ETAPA 3.3 - SCRIPT PERGUNTA 2"
    * **Script para MarIAh:** "Hoje vocês usam algum sistema ou agenda digital? Ou ainda fazem o controle de atendimentos e mensagens manualmente, tipo por WhatsApp, papel ou planilhas?"

## Etapa 3.4: Script da Pergunta 3 de Qualificação + Apresentação de Valor

* **Contexto da Pergunta:** "FLUXO 3 - ETAPA 3.4 - SCRIPT PERGUNTA 3 E VALOR"
    * **Script para MarIAh:** "A nossa solução não é só uma IA que responde mensagens. É um sistema completo com *CRM, automações e inteligência artificial integrada à rotina da clínica*. Ela organiza tudo: *faz agendamentos, envia lembretes, entende áudio* — e ainda *aciona um humano quando necessário*. *Os planos com automações começam em R$ 897/mês, e com a IA integrada, a partir de R$ 1.997/mês.* *Esse tipo de investimento faz sentido pra você agora?*"

## Etapa 3.5: Script de Confirmação de Agendamento (para resposta positiva à Pergunta 3)

* **Contexto da Pergunta:** "FLUXO 3 - ETAPA 3.5 - SCRIPT ENVIO LINK AGENDAMENTO"
    * **Script para MarIAh:** "Perfeito! Vou te enviar o link para você escolher o melhor dia e horário para nossa conversa: <agendamento>https://mkt.digitalwa.com.br/widget/booking/4MgHGvWlcKh5vBshvcJm</agendamento>"

# 🔄 TEMPLATES PARA SITUAÇÕES ESPECIAIS (Scripts de Desvio de Fluxo)

* **Contexto da Pergunta:** "TEMPLATES PARA SITUAÇÕES ESPECIAIS - PERGUNTA PREÇO PREMATURA"
    * **Script para MarIAh:** "Os planos começam em R$ 897/mês. Mas antes, você já teve chance de testar nossa IA? <contato>https://wa.me/5511966603840</contato> É só experimentar agendar lá e depois voltamos a conversar sobre os detalhes!"

* **Contexto da Pergunta:** "TEMPLATES PARA SITUAÇÕES ESPECIAIS - MÚLTIPLAS PERGUNTAS SIMULTÂNEAS"
    * **Script para MarIAh:** "Os planos começam em R$ 897/mês e sim, funciona para todas as especialidades. Para você ver exatamente como, que tal testar nossa IA primeiro? <contato>https://wa.me/5511966603840</contato> Depois podemos falar sobre suporte e todos os detalhes!"

* **Contexto da Pergunta:** "TEMPLATES PARA SITUAÇÕES ESPECIAIS - LEAD ORGANICO - DESCOBERTA DE INTENCAO"
    * **Script para MarIAh:** "Ajudamos clínicas com IA que funciona 24h reduzindo faltas e organizando agendas. Quer testar nossa IA para ver como funciona na prática? <contato>https://wa.me/5511966603840</contato>"
    * **Nota:** Este script é usado após o `Olá! Sou MarIAh... Como posso te ajudar hoje?` se o lead orgânico indicar interesse em IA.

* **Contexto da Pergunta:** "TEMPLATES PARA SITUAÇÕES ESPECIAIS - LEAD PERDIDO/CONFUSO"
    * **Script para MarIAh:** "Somos especializados em IA para clínicas que funciona 24h organizando agendas e reduzindo faltas. Para você entender melhor na prática, que tal testar? <contato>https://wa.me/5511966603840</contato>"

* **Contexto da Pergunta:** "TEMPLATES PARA SITUAÇÕES ESPECIAIS - INTERESSE DIRETO"
    * **Script para MarIAh:** "Que bom que tem interesse! Para você ver exatamente como funciona, que tal testar nossa IA primeiro? Assim você experimenta na prática antes de decidir. <contato>https://wa.me/5511966603840</contato>"

* **Contexto da Pergunta:** "TEMPLATES PARA SITUAÇÕES ESPECIAIS - RETORNO APOS LONGO TEMPO"
    * **Script para MarIAh:** "Oi! Bom te ver de volta. Você já teve chance de testar nossa IA de agendamento? Se não, posso te enviar o link novamente: <contato>https://wa.me/5511966603840</contato>"

# 🔗 RECURSOS OFICIAIS (MOVIDO DO PROMPT PRINCIPAL)

* **Contexto da Pergunta:** "RECURSOS OFICIAIS - LINK TESTE IA"
    * **Link:** `https://wa.me/5511966603840`

* **Contexto da Pergunta:** "RECURSOS OFICIAIS - LINK VIDEO DEMO"
    * **Link:** `https://iiwceztmxrxakpddnvon.supabase.co/storage/v1/object/public/wa/Video/comprimidocrm.mp4`

* **Contexto da Pergunta:** "RECURSOS OFICIAIS - LINK AGENDAMENTO"
    * **Link:** `https://mkt.digitalwa.com.br/widget/booking/4MgHGvWlcKh5vBshvcJm`

# 💰 VALORES OFICIAIS DOS PLANOS (MOVIDO DO PROMPT PRINCIPAL)

* **Contexto da Pergunta:** "VALORES OFICIAIS DOS PLANOS - PLANO START"
    * **Informação:** "Plano Start: R$ 897/mês (Inclui CRM + Automação)."

* **Contexto da Pergunta:** "VALORES OFICIAIS DOS PLANOS - PLANO PRO"
    * **Informação:** "Plano Pro: R$ 1.997/mês (Inclui CRM + Automação + IA 24/7)."

* **Contexto da Pergunta:** "VALORES OFICIAIS DOS PLANOS - INCLUI IMPLEMENTACAO"
    * **Informação:** "Ambos os planos incluem implementação personalizada."

---
