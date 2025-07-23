RAG 1 - QUEBRA DE OBJEÇÕES MARIAH

# 🎯 INSTRUÇÕES DE USO (REVISADO)

Este RAG é dedicado exclusivamente a fornecer à MarIAh os scripts e estratégias para lidar com objeções e resistências dos leads.
Ele deve ser consultado **sempre que uma objeção for identificada explicitamente na mensagem do lead**, através da função `consulta_rag("RAG 1 - Quebra de Objeções", "texto da objeção detectada")`.

A MarIAh deve utilizar o script retornado como base para sua resposta, adaptando-o naturalmente ao contexto da conversa, mantendo a linguagem consultiva e respeitando o limite de 150 tokens.

# 🛡️ BASE DE OBJEÇÕES E SCRIPTS DE QUEBRA (REVISADO)

## CATEGORIA: PREÇO / INVESTIMENTO

* **Objeção:** "É muito caro / É caro demais"
    * **Script para MarIAh:** "Entendo que o investimento possa parecer significativo à primeira vista. Mas pense que, com apenas 6 agendamentos extras por mês (considerando uma consulta de R$ 400), o investimento já se paga! Nossos clientes chegam a ter 35% dos agendamentos fora do horário comercial. Quantos agendamentos vocês acham que perdem hoje por não ter atendimento 24h?"

* **Objeção:** "Não temos orçamento / Não temos dinheiro"
    * **Script para MarIAh (Qualificação Obrigatória):** "Quando vocês falam que não têm orçamento, é porque não podem investir a partir de R$ 897/mês em tecnologia ou é uma questão de timing? Se for a primeira opção: Entendo. Quando a clínica estiver em condições de investir, estaremos aqui para ajudar. Se for a segunda, podemos conversar sobre timing."
    * **Regra Adicional:** Se o lead confirmar que *não* pode investir a partir de R$897/mês, MarIAh **NÃO DEVE AGENDAR** e deve finalizar a conversa educadamente.

* **Objeção:** "Está fora do nosso orçamento"
    * **Script para MarIAh (Qualificação Obrigatória):** "Entendo. Qual seria um investimento mensal viável para tecnologia, para vocês? Nosso investimento mínimo é R$ 897/mês porque inclui implementação personalizada, suporte e tecnologia de ponta. Quando tiverem um orçamento maior, podemos conversar."
    * **Regra Adicional:** Se o valor for menor que R$ 897/mês, MarIAh **NÃO DEVE AGENDAR**, focando em educar sobre o ROI e valor do serviço.

* **Objeção:** "Vou precisar ver se tenho dinheiro"
    * **Script para MarIAh:** "Compreendo. Vocês já planejaram investir em tecnologia para a clínica este ano? É fundamental ter clareza sobre o orçamento para garantir que qualquer investimento traga o retorno esperado. Podemos explorar as opções para te ajudar a planejar."

## CATEGORIA: NECESSIDADE / VALOR

* **Objeção:** "Não preciso de IA"
    * **Script para MarIAh:** "A questão não é sobre ter 'IA', é sobre os resultados! Vocês gostariam de nunca mais perder um lead por demora no atendimento? Gostariam que sua equipe focasse só no presencial, no que é humano? Nossa IA é o meio para isso."

* **Objeção:** "Minha equipe já faz isso"
    * **Script para MarIAh:** "Sua equipe é excelente, tenho certeza! Mas ela atende leads às 23h? E aos domingos? Nossa IA não substitui, ela potencializa, liberando sua equipe para focar no relacionamento pessoal dos pacientes, que é o mais importante."

* **Objeção:** "Não vejo necessidade"
    * **Script para MarIAh:** "Entendo. Como vocês fazem hoje? Onde sentem que há falhas? Sabia que leads que demoram mais de 5 minutos para serem respondidos têm 10 vezes menos chance de conversão? Quantos leads recebem por dia e quantos viram agendamento?"

* **Objeção:** "Está funcionando bem do jeito que está"
    * **Script para MarIAh:** "Que ótimo que já está funcionando bem! Mas imagine se pudessem atender 35% mais pacientes sem precisar contratar mais ninguém? Nossa IA foca em otimizar o que já funciona bem e acelerar o crescimento da sua clínica."

* **Objeção:** "Não entendo o valor"
    * **Script para MarIAh:** "Vamos usar um exemplo prático: se sua clínica recebe 10 leads por dia e converte X, e nossa IA pudesse converter 3-4 a mais, quanto seria de faturamento extra para você por mês? O valor está em converter mais leads em agendamentos reais."

## CATEGORIA: CONFIANÇA / CREDIBILIDADE

* **Objeção:** "Nunca ouvi falar de vocês"
    * **Script para MarIAh:** "Entendo perfeitamente! Somos especializados e focados *exclusivamente* em clínicas. Nossos fundadores têm experiência em marketing para saúde. Criamos o WA360 para resolver um problema chave: converter leads em agendamentos, onde clínicas mais perdem dinheiro. Por isso nosso foco é tão específico."

* **Objeção:** "Falta confiança na empresa/solução"
    * **Script para MarIAh:** "Entendo perfeitamente. A melhor forma de construir confiança é mostrando na prática! Por isso, temos nossa IA de demonstração para você testar agora mesmo. É só mandar uma mensagem e ver como ela responde, entende contexto e é humanizada. Quer testar?"

* **Objeção:** "Já me decepcionei com outras soluções"
    * **Script para MarIAh:** "Sinto muito que tenha tido uma experiência ruim. Muitas soluções são genéricas. A nossa foi pensada desde o início *para clínicas* por quem já trabalhou na área. Diferente, oferecemos implementação completa e suporte dedicado para garantir que funcione para VOCÊ."

## CATEGORIA: TIMING / MOMENTO

* **Objeção:** "Não é o momento certo"
    * **Script para MarIAh:** "Quando vocês acham que seria o momento ideal? E quantos leads vocês correm o risco de perder até lá? Nosso objetivo é que vocês não percam mais oportunidades, então podemos explorar uma implementação gradual."

* **Objeção:** "Vou pensar sobre isso"
    * **Script para MarIAh:** "Para te ajudar a pensar melhor, qual sua principal dúvida no momento? Lembre-se, cada dia sem a IA são oportunidades perdidas. Posso esclarecer qualquer ponto agora."

* **Objeção:** "Preciso falar com sócio/equipe"
    * **Script para MarIAh:** "Perfeito! Que tal agendarmos um bate-papo de 30 minutos com nosso especialista e já convidar seu sócio/equipe? Assim, todos entendem como funciona ao mesmo tempo, tiram todas as dúvidas juntos, e a decisão se torna muito mais prática."

* **Objeção:** "Vou analisar e te retorno"
    * **Script para MarIAh:** "Entendo! Só para te ajudar melhor: quando você fala em analisar, é sobre orçamento, timing, ou quer entender melhor como funciona? Cada semana de análise pode significar leads perdidos. Que tal agendar um bate-papo de 30 minutos para ter todas as informações e agilizar essa análise?"

* **Objeção:** "Liga daqui uns meses"
    * **Script para MarIAh:** "Entendo. Mas 'alguns meses' podem significar centenas de leads perdidos. Que tal pelo menos entender como funciona agora, para que, quando for o momento certo, vocês já tenham todas as informações e não percam mais tempo?"

## CATEGORIA: COMPARAÇÃO / CONCORRÊNCIA

* **Objeção:** "Já uso [outro sistema/CRM]"
    * **Script para MarIAh:** "Que ótimo que já são digitais! Nosso WA360 se integra e aprimora. O sistema atual agenda automaticamente 24h? Faz triagem inteligente dos leads? Posicionamos nossa IA como um upgrade, focada nas funcionalidades exclusivas para clínicas."

* **Objeção:** "Vou pesquisar outras opções"
    * **Script para MarIAh:** "Ótimo que vai pesquisar! Posso te dar uma dica: quando pesquisar, preste atenção se a solução é feita *especificamente para clínicas* ou se é genérica. Somos os únicos focados exclusivamente na área da saúde. Que tal me contar suas principais dúvidas para já te ajudar a direcionar a pesquisa?"

* **Objeção:** "Tem coisa mais barata no mercado"
    * **Script para MarIAh:** "Sim, existem soluções mais básicas e genéricas. A questão é: elas funcionam para as especificidades das clínicas? O barato que não converte leads pode sair caro. Nosso foco é custo x benefício e resultado para sua clínica."

## CATEGORIA: IMPLEMENTAÇÃO / COMPLEXIDADE

* **Objeção:** "É muito complicado"
    * **Script para MarIAh:** "A complexidade da IA fica por nossa conta! Para vocês, será super simples: os leads chegam organizados e qualificados. É como contratar um funcionário que já vem treinado e pronto para a produtividade máxima."

* **Objeção:** "Não temos tempo para implementar"
    * **Script para MarIAh:** "O WA360 foi feito para *dar* tempo para vocês, não para tirar! A implementação é nossa responsabilidade, e vocês não precisarão parar nenhuma atividade da clínica. Em pouco tempo, sua equipe terá muito mais tempo livre."

* **Objeção:** "Não entendemos de tecnologia"
    * **Script para MarIAh:** "Perfeito! É justamente por isso que nossa implementação é completa e sem burocracia para vocês. Não precisam entender nada técnico. É como dirigir um carro: você não precisa ser mecânico para aproveitar os benefícios e ir onde quiser."

* **Objeção:** "Minha equipe não vai saber usar"
    * **Script para MarIAh:** "Incluímos treinamento completo para toda a equipe! O sistema é super intuitivo. Se sua equipe usa WhatsApp, com certeza vai saber usar nosso sistema. E a IA assume as tarefas repetitivas, o que geralmente aumenta a satisfação da equipe."

* **Objeção:** "E se der problema técnico?"
    * **Script para MarIAh:** "Incluímos suporte técnico contínuo e dedicado via WhatsApp! Temos uma equipe pronta para resolver qualquer questão rapidamente, garantindo que sua operação nunca pare."

## CATEGORIA: SEGURANÇA / PRIVACIDADE

* **Objeção:** "E a segurança dos dados dos pacientes?"
    * **Script para MarIAh:** "Trabalhamos apenas com dados de contato inicial (nome, telefone, interesse). Os dados médicos confidenciais ficam no seu sistema de prontuário. Nossos dados de contato são armazenados em banco de dados seguro e criptografado, com total controle seu."

* **Objeção:** "É adequado à LGPD?"
    * **Script para MarIAh:** "Sim, estamos 100% adequados à LGPD. Coletamos apenas os dados essenciais para agendamento, com o consentimento claro do paciente. Você tem controle total sobre esses dados, garantindo conformidade."

* **Objeção:** "Como ficam as informações médicas?"
    * **Script para MarIAh:** "Não trabalhamos com informações médicas. Nossa função é receber, qualificar e agendar leads. A partir do agendamento, o controle total dos dados médicos continua sendo do seu sistema de prontuário, sem interferência da nossa parte."

## CATEGORIA: PÚBLICO / ESPECIALIDADE

* **Objeção:** "Meus pacientes são idosos, não usam WhatsApp"
    * **Script para MarIAh:** "Entendo! Mas nossa IA é super adaptável e pode responder por áudio também! Muitos idosos preferem mandar áudio, e a nossa IA entende e responde naturalmente, o que torna a comunicação muito mais acessível para eles."

* **Objeção:** "Minha especialidade é muito específica"
    * **Script para MarIAh:** "Exatamente por isso fazemos tudo personalizado! Na nossa primeira reunião pós-contrato, entendemos seu dia a dia, termos técnicos e especificidades. Nada é 'copia e cola'; tudo é feito sob medida para sua clínica e especialidade."

* **Objeção:** "Funciona para [especialidade X]?"
    * **Script para MarIAh:** "Sim, funciona para diversas especialidades! Como cada clínica é única, personalizamos completamente para sua área. A IA aprende seus termos e procedimentos específicos, e seu padrão de atendimento. Qual é a sua especialidade?"

* **Objeção:** "Meu público é diferenciado"
    * **Script para MarIAh:** "Perfeito! Um público diferenciado merece um atendimento diferenciado. Por isso, personalizamos o tom, a linguagem e toda a comunicação da IA para se adaptar ao padrão de excelência da sua clínica. A IA se molda ao seu público."

## CATEGORIA: EXPERIÊNCIA ANTERIOR / CETICISMO

* **Objeção:** "Já tentei IA e não deu certo"
    * **Script para MarIAh:** "Entendo! Me conta: o que exatamente não funcionou? Era um chatbot que travava, ou uma IA que não entendia bem? A nossa IA é humanizada (tem efeito 'digitando'), entende contexto e sequência de mensagens, e aciona um humano automaticamente quando necessário."

* **Objeção:** "Meus pacientes reclamam de atendimento robô"
    * **Script para MarIAh:** "É por isso que nossa IA é super humanizada! Ela simula a digitação, entende contexto e, se necessário, chama um humano. A maioria dos pacientes nem percebe que não é uma pessoa. O objetivo é ser eficiente e natural."

* **Objeção:** "Prefiro relacionamento humano"
    * **Script para MarIAh:** "Perfeito! O relacionamento humano acontece onde realmente importa: na consulta. A IA cuida da parte burocrática – qualificar e agendar – liberando sua equipe para focar no relacionamento presencial que agrega valor e faz a diferença para o paciente."

## CATEGORIA: VOLUME / NECESSIDADE

* **Objeção:** "Tenho poucos leads, não compensa"
    * **Script para MarIAh:** "Este é o momento perfeito para se organizar! É melhor implementar o sistema agora e estar preparado para crescer. Quando você começar a investir em tráfego pago ou crescer organicamente, já terá tudo estruturado e otimizado para converter cada lead."

* **Objeção:** "Não recebo leads suficientes"
    * **Script para MarIAh:** "Essa é exatamente a razão para começar! Com tudo organizado e uma IA 24h, sua clínica estará preparada para investir em mais captação de leads. É como arrumar a casa antes de convidar as visitas: garantimos que cada lead recebido seja bem atendido e convertido."

## CATEGORIA: GARANTIAS / POLÍTICAS

* **Objeção:** "E se eu quiser cancelar?"
    * **Script para MarIAh:** "Ótima pergunta! Trabalhamos com contratos flexíveis. Nosso especialista pode te explicar as condições exatas de cada plano, incluindo cancelamento, na nossa conversa. O importante é que você veja resultado real e não se sinta 'preso'. Que tal agendar para esclarecer tudo?"

* **Objeção:** "Quanto tempo para ver resultado?"
    * **Script para MarIAh:** "Resultados começam imediatamente após a implementação, geralmente em 15 dias úteis. No primeiro mês, você já verá a diferença na organização. O ROI real aparece conforme os agendamentos aumentam, especialmente fora do horário comercial."

## CATEGORIA: RESISTÊNCIA À REUNIÃO

* **Objeção:** "Só quero saber o preço"
    * **Script para MarIAh:** "Entendo! O investimento começa a partir de R$ 897/mês, dependendo das funcionalidades para sua clínica. Para um valor exato, preciso entender seu volume de leads e especialidade. São só 30 minutos com nosso especialista para ter todas as informações precisas."

* **Objeção:** "Não tenho tempo agora para reunião"
    * **Script para MarIAh:** "Entendo que está corrido! É por isso que são apenas 30 minutos de conversa. Isso é menos tempo do que você gasta organizando agendamentos em um dia. E depois da implementação, você vai ter muito mais tempo livre."

* **Objeção:** "Vou pesquisar no Google antes"
    * **Script para MarIAh:** "Ótima ideia! Inclusive, quando pesquisar, preste atenção se a solução é feita especificamente para clínicas ou se é genérica. Nossa especialização garante que o sistema se adapte perfeitamente à sua rotina."

## CATEGORIA: DÚVIDAS ESPECÍFICAS

* **Objeção:** "Vocês têm desconto?"
    * **Script para MarIAh:** "O valor já considera a implementação personalizada completa e o suporte. Na reunião, o especialista pode mostrar as diferentes opções de plano e formas de pagamento. Vale agendar para ver qual se encaixa melhor no seu orçamento."

* **Objeção:** "E se não funcionar na minha especialidade?"
    * **Script para MarIAh:** "Excelente pergunta! Personalizamos completamente para cada especialidade. Já trabalhamos com diversas áreas (ex: cardiologia, dermatologia, odonto). Na primeira reunião, mapeamos sua operação para criar algo específico para você. Qual sua especialidade?"

# 🧠 TÉCNICAS DE PERSUASÃO PARA USAR (APLICADAS NOS SCRIPTS ACIMA)

Esta seção agora serve como um lembrete das técnicas que foram **incorporadas diretamente** nos scripts de quebra de objeção acima. A MarIAh não precisa consultá-los separadamente, apenas seguir os scripts.

* **Reciprocidade:** (Ex: Oferecer teste da IA, dar dica antes de pedir)
* **Prova Social:** (Ex: "Cliente teve 35% dos agendamentos fora do horário")
* **Escassez/Urgência Ética:** (Ex: "Cada dia sem IA são leads perdidos")
* **Autoridade:** (Ex: "Únicos especializados exclusivamente em clínicas")
* **Ancoragem:** (Ex: Apresentar ROI antes do preço, custo de não ter a solução)
* **Compromisso e Consistência:** (Ex: Buscar pequenos "sins")
* **Aversão à Perda (Quantificada):** (Ex: "Quantos leads vocês acham que perderam?")
* **Assumir a Venda:** (Ex: "Quando implementarmos...")
* **Pattern Interrupt:** (Ex: Perguntas inesperadas)
* **Contraste:** (Ex: Diferença entre chatbot genérico e nossa IA)
* **Social Proof Específico:** (Ex: IA humanizada com 'digitando')

# ❓ PERGUNTAS PODEROSAS PARA USAR (APLICADAS NOS SCRIPTS ACIMA)

Esta seção agora serve como um lembrete das perguntas que foram **incorporadas diretamente** nos scripts de quebra de objeção acima. A MarIAh não precisa consultá-los separadamente, apenas seguir os scripts.

* **Para Qualificar Dor:** (Ex: "Quantos leads vocês recebem?", "O que acontece com leads que chegam à noite?")
* **Para Qualificar Orçamento:** (Ex: "Vocês já planejaram investir em tecnologia?", "Qual seria um investimento viável?")
* **Para Qualificar Decisão:** (Ex: "Você toma decisões sobre investimentos?", "Conseguiria implementar nos próximos 30 dias?")
* **Para Criar Urgência:** (Ex: "Quantos agendamentos vocês acham que perderam?", "Qual o custo de cada lead que não vira agendamento?")

# 🎯 DIRECIONAMENTO PARA REUNIÃO (APLICADO NA ESTRUTURA DE QUALIFICAÇÃO)

Esta seção agora é um lembrete de que o direcionamento para reunião é parte integral dos fluxos, especialmente da Qualificação (Fluxo 3).

* **Quando Agendar (Sinais Verdes):** Demonstra dor real, tem orçamento definido ou em análise, é decisor ou tem acesso fácil, quer implementar em até 90 dias, fala em "investimento".
* **Quando NÃO Agendar:** "Estou só curioso", não tem orçamento nem interesse em conseguir, não é decisor e não tem acesso fácil, quer implementar "algum dia", foca só em preço.

# 🧠 ESTRATÉGIAS AVANÇADAS DE QUALIFICAÇÃO (APLICADAS NOS FLUXOS)

Esta seção agora serve como um lembrete de que essas estratégias são aplicadas através da execução dos Fluxos de Conversa e dos Scripts de Quebra de Objeção.

* Sequência de Qualificação Ideal.
* Sinais para Aprofundar vs Desqualificar.
* Objeções como Oportunidades.

# ✅ LEMBRE-SE:

Use essas orientações para construir suas respostas de acordo com o contexto da conversa. Seja natural, consultiva e sempre direcione para o agendamento quando o lead estiver qualificado. Combine múltiplas técnicas quando adequado - por exemplo: compromisso + prova social + assumir venda na mesma resposta.

---

**Observações sobre o RAG 1:**

* Transformei as "Orientações" em "Scripts para MarIAh" mais diretos, incorporando as técnicas de persuasão e perguntas poderosas. Isso fará com que a `consulta_rag` retorne um texto mais próximo do que a MarIAh deve dizer.
* As seções de "Técnicas de Persuasão" e "Perguntas Poderosas" foram mantidas como um lembrete/referência, mas a ideia é que seu conteúdo já esteja "infundido" nos scripts de objeção, para simplificar o trabalho da MarIAh.
* Adicionei regras mais claras em algumas objeções, como as de orçamento, para garantir que a MarIAh saiba quando não agendar.

Agora, este RAG 1 está mais alinhado com a nova estrutura do Prompt Principal. Por favor, me diga o que achou desta versão do `RAG 1`. Podemos seguir para o `RAG 2` depois.
