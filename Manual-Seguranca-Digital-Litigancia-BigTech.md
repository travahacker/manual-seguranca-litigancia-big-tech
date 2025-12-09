# Manual de Segurança Digital Para Litigância Contra a Big Tech

**Por Código Não Binário**  
www.codigonaobinario.org | contato@codigonaobinario.org

---

## 1. Introdução

Este manual foi desenvolvido especificamente para organizações que atuam na defesa dos direitos da população LGBTQIAPN+ e que se encontram em contextos de advocacy, ações judiciais ou campanhas públicas contra violações de direitos humanos digitais. Quando organizações se posicionam publicamente, especialmente em ações legais contra grandes corporações tecnológicas, tornam-se alvos potenciais de vigilância, ataques coordenados, vazamento de informações e campanhas de desinformação.

As Big Techs (empresas como Meta/Facebook, Google, X/Twitter e TikTok) não são apenas plataformas neutras. Elas atuam como organismos de vigilância que podem monitorar atividades de organizações críticas, especialmente quando essas organizações estão envolvidas em ações legais ou campanhas que ameaçam seus modelos de negócio ou políticas. Como demonstrado em casos como o lobby contra o PL das Fake News, essas empresas têm capacidade e histórico de monitorar e interferir em processos que as afetam.

Este manual orienta sobre como organizações podem proteger suas comunicações, dados estratégicos e processos internos quando estão envolvidas em ações coletivas, especialmente aquelas que confrontam interesses de grandes corporações tecnológicas. A segurança digital organizacional é diferente da segurança individual: envolve proteger informações compartilhadas entre equipes, manter sigilo sobre estratégias legais e garantir que comunicações não sejam interceptadas ou manipuladas.

A segurança não é opcional quando se está em uma Ação Civil Pública contra plataformas digitais. É essencial.

---

## 2. Por Que Não Usar Plataformas das Ré em Ações Legais

Quando sua organização está envolvida em uma Ação Civil Pública contra empresas como Meta, Google, X ou TikTok, utilizar as plataformas dessas mesmas empresas para comunicação interna, armazenamento de documentos ou coordenação da ação representa um risco crítico de segurança.

### 2.1. Risco de Vigilância Corporativa

As Big Techs têm acesso direto aos dados gerados em suas plataformas. Isso significa que e-mails no Gmail podem ser acessados pela Google, documentos no Google Drive estão sob controle total da Google, comunicações no WhatsApp ou Messenger podem ser monitoradas pela Meta, e postagens e mensagens no X/Twitter são analisadas pela empresa. Ao usar essas plataformas durante uma ação legal contra elas, você está potencialmente fornecendo informações estratégicas diretamente à parte contrária.

### 2.2. Histórico de Interferência em Processos

Evidências demonstram que essas empresas monitoram ativamente grupos críticos e organizações de direitos humanos. Elas realizam lobby agressivo contra regulamentações, como foi o caso do PL das Fake News, do Marco Civil da Internet, da LGPD (Lei Geral de Proteção de Dados) e da discussão sobre regulação de plataformas digitais no Congresso Nacional. Compartilham dados com governos e terceiros quando convém. E usam algoritmos para suprimir ou amplificar conteúdos conforme seus interesses, criando um ambiente onde o controle da informação serve a seus objetivos de negócio.

### 2.3. Vulnerabilidades Legais

Documentos estratégicos armazenados em plataformas controladas pela parte contrária podem ser acessados em processos de descoberta de evidências, também conhecido como discovery. Podem se tornar objeto de solicitações legais de terceiros. Podem ser analisados por algoritmos de vigilância interna das próprias empresas. E ficam sujeitos a termos de serviço que permitem acesso da empresa quando ela considerar necessário.

### 2.4. Alternativas Necessárias

Este manual fornece alternativas seguras para cada função que tradicionalmente seria realizada em plataformas das Big Techs, garantindo que sua organização possa operar de forma segura durante processos legais sensíveis.

---

## 3. Comunicação Segura Entre Organizações

A comunicação entre organizações parceiras em uma ACP precisa ser protegida contra interceptação, vazamento e monitoramento.

### 3.1. E-mail Seguro (Alternativa ao Gmail)

Para e-mail, esqueçam Gmail, Outlook e Yahoo Mail. Esses serviços estão todos nas mãos de Big Techs ou têm histórico ruim de privacidade. Em vez disso, usem ProtonMail, um serviço de e-mail criptografado de ponta a ponta baseado na Suíça, com foco em privacidade. Tutanota é uma alternativa alemã com criptografia automática. Mailbox.org também é alemão, respeita a privacidade e não depende de Big Techs.

Para maior segurança, configurem autenticação em dois fatores (veja seção 8.3) e usem senhas fortes geradas por gerenciadores de senhas. Para e-mails realmente sensíveis, ativem criptografia PGP ou GPG - pode ter uma curva de aprendizado, mas é essencial para comunicação estratégica. E façam endereços de e-mail específicos só para comunicação da ACP, não misturem com e-mails pessoais ou de outros projetos.

### 3.2. Mensagens Instantâneas (Alternativa ao WhatsApp)

WhatsApp está fora de questão - é da Meta. Messenger também. Telegram até tem mais privacidade, mas ainda assim não é ideal para informações estratégicas de uma ACP. Signal é a melhor opção disponível. É o que especialistas em segurança recomendam, tem criptografia de ponta a ponta e não é controlado por Big Techs. Element, que usa a plataforma Matrix, é outra opção boa, descentralizada. Briar também funciona bem, especialmente se vocês quiserem algo peer-to-peer que não depende de servidores centralizados.

Quando usarem Signal ou outras ferramentas, configurem mensagens para auto-destruição após um período determinado. Usem grupos fechados só com membros que vocês verificaram pessoalmente. Desativem notificações na tela de bloqueio para mensagens sensíveis - não precisa todo mundo ver que alguém está recebendo mensagem sobre a ACP. E revisem regularmente quem tem acesso aos grupos, porque pessoas saem de organizações, mudam de função, e o acesso precisa ser cortado.

### 3.3. Videoconferências (Alternativa ao Zoom/Meet)

Google Meet não, é da Google. Zoom também tem histórico ruim de vigilância e é empresa americana. Jitsi Meet é open-source e pode até ser auto-hospedado se vocês tiverem suporte técnico. BigBlueButton também é open-source e focado em privacidade. Element Video oferece videoconferência integrada à plataforma Matrix.

Sempre ativem salas com senha. Usem "waiting room" para controlar quem entra. E se vocês precisam gravar, façam localmente no computador de alguém - não deixem gravações na nuvem onde podem ser acessadas por terceiros. Para reuniões muito sensíveis, usem VPN (veja seção 10.1).

---

## 4. Armazenamento e Compartilhamento de Documentos

Documentos estratégicos de uma ACP não devem ser armazenados em plataformas controladas pela parte contrária. Essa é uma das partes mais críticas da segurança organizacional.

### 4.1. Armazenamento em Nuvem (Alternativa ao Google Drive)

Google Drive, Dropbox e OneDrive estão fora. Esses serviços estão todos nas mãos de Big Techs ou têm acesso a dados que vocês não controlam. Nextcloud é uma excelente alternativa - é open-source, pode ser auto-hospedado se vocês tiverem suporte técnico, e vocês têm controle total. ProtonDrive vem da mesma empresa do ProtonMail, então já tem a confiança estabelecida. Tresorit é suíço, focado em segurança empresarial, mais caro mas confiável. CryptPad é interessante porque é criptografado de ponta a ponta, até mesmo quem hospeda não consegue ver o conteúdo.

Para documentos realmente estratégicos da ACP, criptografem antes de fazer upload - uma camada extra de segurança nunca faz mal. Configurem acesso baseado em papéis: nem todo mundo precisa acessar tudo. Mantenham backups locais em dispositivos seguros - não confiem só na nuvem. E quando precisarem compartilhar algo, usem links com senha e data de expiração. Link que nunca expira é receita para problema.

### 4.2. Edição Colaborativa de Documentos

Google Docs está fora. Microsoft 365 online também. CryptPad tem editor colaborativo criptografado - pode ser meio estranho no começo, mas funciona. OnlyOffice pode rodar no próprio servidor de vocês. Etherpad é mais simples, mas também seguro.

Quando trabalhar em documentos sensíveis, criptografem localmente antes de sincronizar, revisem histórico de acesso regularmente, e removam acesso de quem não participa mais do projeto. Mantenham versões locais criptografadas também - nunca se sabe quando vão precisar.

### 4.3. Backup Seguro

Para documentos estratégicos, sempre mantenham backups locais em dispositivos seguros - não confiem só na nuvem. Criptografem backups antes de armazenar e usem serviços que não sejam controlados por Big Techs. Para estratégias completas de backup e recuperação, consulte a seção 12.3.

---

## 5. Gerenciamento de Informações Sensíveis

Organizações envolvidas em ACPs precisam gerenciar informações altamente sensíveis: estratégias legais, documentos processuais, comunicação com advogados, evidências coletadas, entre outros.

### 5.1. Classificação de Informações

Classifiquem as informações por nível de sensibilidade. Público é o que pode ser compartilhado publicamente. Interno é só para uso dentro da organização. Confidencial é o que, se vazar, pode prejudicar a ACP. E ultra confidencial é o que pode comprometer toda a ação se alguém de fora descobrir - essas informações só devem circular entre quem precisa saber.

### 5.2. Compartilhamento Controlado

Não é questão de não confiar na equipe - é questão de segurança. Quanto menos gente souber de detalhes estratégicos, menor a chance de vazamento, seja por descuido, seja por ataque. Implementem o princípio "necessidade-de-saber": pessoas só acessam o que precisam para fazer o trabalho delas. Mantenham log de quem acessou o quê e quando - quando algo der errado, vocês vão precisar disso. E mantenham permissões atualizadas conforme pessoas mudam de função ou saem de projetos.

### 5.3. Proteção de Documentos Processuais

Documentos processuais da ACP devem ser criptografados antes de armazenar. Sem exceção. Discussões sobre estratégias devem ser em comunicação criptografada - não fiquem mencionando detalhes sensíveis em e-mails normais ou mensagens não seguras. E quando possível, mantenham documentos processuais em sistemas isolados - não precisa tudo estar misturado com outros projetos da organização.

### 5.4. Comunicação com Equipe Jurídica

A comunicação com a equipe jurídica precisa de cuidado especial. Estabeleçam um canal seguro exclusivo só para isso. Para documentos legais, usem e-mail criptografado com PGP. Não discutam estratégias legais em plataformas que não são criptografadas - mesmo que pareça mais prático, não vale o risco. E mantenham backup seguro de toda comunicação jurídica - vocês podem precisar desse histórico depois.

---

## 6. Redes Sociais e Comunicação Pública

Mesmo que sua organização não use plataformas das Ré para comunicação interna, pode precisar usá-las para comunicação pública. Isso requer estratégias específicas.

### 6.1. Separação de Contas

Primeiro, separem completamente contas profissionais de contas pessoais. Não dá pra misturar. Se possível, usem dispositivos diferentes ou pelo menos perfis separados. E não conectem contas profissionais da organização a outros serviços de Big Techs - cada conta isolada, senha única. Quando acessarem essas contas, sempre usem VPN (consulte seção 10.1). Pode parecer exagero, mas vocês estão numa ACP contra essas empresas. Não subestimem o que elas podem fazer.

### 6.2. Estratégias de Comunicação Pública

Quando precisarem usar essas plataformas para alcance público, lembrem-se: essas são comunicações públicas, não internas. Não discutam estratégias internas ou detalhes da ACP nessas plataformas - nunca. Usem linguagem que comunica a mensagem sem revelar informações confidenciais. Coordenem o que vão publicar através de canais seguros antes - não improvisem em plataformas que vocês não controlam. E quando houver reações - e vão ter - monitorem, mas não discutam estratégias em resposta. Pessoas podem tentar fazer vocês revelarem informações ao responder comentários.

### 6.3. Proteção de Perfis Organizacionais

Protejam os perfis organizacionais ao máximo. Ativem autenticação em dois fatores em todas as contas (veja seção 8.3). Usem senhas únicas e fortes para cada plataforma, gerenciadas por um gerenciador de senhas. Monitorem acessos e alterações nas contas regularmente. E tenham um plano de recuperação caso as contas sejam hackeadas ou comprometidas - porque pode acontecer.

### 6.4. Alternativas para Comunicação Pública

Mas quando possível, priorizem alternativas. Site próprio da organização, hospedado em servidores independentes, dá muito mais controle. Newsletter por e-mail, usando serviços seguros, também funciona bem. Mastodon e outras plataformas federadas podem ser uma opção dependendo da audiência de vocês. O ideal é reduzir dependência dessas plataformas o máximo possível, mesmo que signifique um alcance menor no curto prazo.

---

## 7. Segurança de Dispositivos Organizacionais

Dispositivos usados para trabalhar na ACP precisam de proteção reforçada. Não dá pra usar o mesmo computador que vocês usam para coisas pessoais e achar que está seguro.

### 7.1. Dispositivos Dedicados

Considerem ter dispositivos dedicados só para trabalho na ACP - pode parecer custo extra, mas se vocês estão numa ação que pode valer milhões, vale o investimento. Separem completamente dispositivos pessoais de organizacionais. Se não puderem ter dispositivos separados, pelo menos usem perfis diferentes no sistema operacional. E pensem em sistemas operacionais focados em privacidade - Linux para computadores, LineageOS para Android. Linux dá mais controle e menos rastreamento. Fisicamente, mantenham dispositivos organizacionais seguros - não deixem notebook da organização em lugares compartilhados sem supervisão.

### 7.2. Atualizações e Manutenção

Mantenham tudo atualizado. Sistemas operacionais, aplicativos, tudo. Atualizações frequentemente corrigem vulnerabilidades de segurança. Em Windows e Mac, usem antivírus confiável - não os gratuitos que só servem para mostrar anúncios. Configurem firewalls para bloquear conexões não autorizadas. E façam varreduras regulares de malware - não esperem dar problema para verificar.

### 7.3. Criptografia de Dispositivos

Criptografia de dispositivos é essencial. Ativem criptografia completa do disco em todos os dispositivos - se alguém roubar ou acessar fisicamente, os dados ainda estarão protegidos. Senhas fortes para desbloqueio, bloqueio automático após período de inatividade. Se vocês têm muitos dispositivos móveis, considerem gerenciamento de dispositivos móveis (MDM) para controlar e proteger de forma centralizada.

### 7.4. Acesso Remoto Seguro

Quando acessarem recursos organizacionais remotamente, sempre usem VPN (veja seção 10.1 para detalhes completos). Redes Wi-Fi públicas são extremamente inseguras - qualquer um na mesma rede pode interceptar o tráfego. Sem VPN, não façam isso. Para acesso remoto, além de VPN, usem autenticação de dois fatores (seção 8.3). E monitorem esses acessos - se alguém está tentando acessar de lugar estranho ou em horários suspeitos, vocês precisam saber.

---

## 8. Senhas e Autenticação

Senhas fracas são um dos maiores problemas de segurança organizacional. Pode ter todas as outras proteções do mundo, mas se as senhas são fracas ou reutilizadas, vocês estão vulneráveis.

### 8.1. Gerenciadores de Senhas

Usem gerenciador de senhas. Não dá mais para confiar em memória ou anotar em papel. Bitwarden é open-source e pode ser auto-hospedado - vocês têm controle total. KeePass é completamente local - os dados nunca saem do computador de vocês. 1Password é comercial mas tem foco em segurança empresarial. Não usem gerenciadores que dependem de Big Techs ou que não são transparentes sobre como funcionam.

### 8.2. Política de Senhas

Política de senhas precisa ser clara e rigorosa. Mínimo de 16 caracteres - mais é melhor. Combinação de letras (maiúsculas e minúsculas), números e símbolos. Proíbam reutilização - cada conta tem sua própria senha única. E para contas críticas, forcem alteração periódica. Pode ser chato, mas é necessário.

### 8.3. Autenticação em Dois Fatores (2FA)

Autenticação em dois fatores não é opcional para contas críticas. É obrigatória. Sem 2FA, se alguém descobrir a senha, já era. Usem aplicativos autenticadores tipo Authy em vez de SMS - SMS pode ser interceptado. E mantenham códigos de recuperação em local seguro e separado - se perderem o celular, vão precisar deles. Revisem regularmente quais dispositivos têm acesso autorizado - removam o que não precisa mais.

### 8.4. Compartilhamento Seguro de Credenciais

Compartilhamento de credenciais precisa ser feito direito. Nunca por e-mail não criptografado ou mensagens não seguras. Gerenciadores de senhas têm opção de compartilhamento seguro - usem isso. E quando alguém sai do projeto, revoguem acesso na hora. Não esperem, não deixem para depois. E monitorem uso de credenciais compartilhadas - se tem muita gente usando, aumenta o risco.

---

## 9. Proteção Contra Ataques Digitais

Quando vocês estão numa ACP contra Big Techs, vocês são alvos. Essas empresas têm recursos para fazer acontecer. Então precisam estar preparados.

### 9.1. Tipos de Ataques Comuns

Doxxing organizacional é comum - expor informações internas, endereços físicos, membros da equipe. Phishing também - e-mails ou sites falsos tentando fazer vocês entregarem credenciais. Ataques DDoS para sobrecarregar servidores e interromper serviços. Comprometimento de contas - hackear e-mails ou redes sociais. E campanhas de desinformação - espalhar mentiras sobre vocês. Tudo isso pode acontecer.

### 9.2. Prevenção

Prevenção começa com educação. Toda a equipe precisa saber reconhecer phishing - treinamento não é opcional. Implementem políticas claras de segurança da informação e façam todo mundo seguir. Para estratégias de backup e recuperação, consulte a seção 12.3. Monitorem menções à organização online - se alguém está tentando criar narrativa falsa sobre vocês, vocês precisam saber rapidamente. E tenham um plano de resposta a incidentes documentado - quando acontecer, não dá tempo de pensar no que fazer.

### 9.3. Resposta a Ataques

Se vocês forem atacados, a primeira coisa é documentar tudo. Screenshots, logs, e-mails - qualquer coisa que possa servir de evidência depois. Isolem sistemas comprometidos imediatamente - não tentem "investigar" enquanto ainda está ativo, cortem o acesso primeiro. Notifiquem toda a equipe sobre o ataque e as medidas de proteção que vocês estão tomando. E considerem notificar autoridades - polícia, Código Não Binário, SaferNet, quem for competente. Se precisarem comunicar publicamente, façam de forma muito controlada - não dêem mais informação do que necessário.

### 9.4. Proteção Específica para ACPs

Para ACPs especificamente, limitem conhecimento de detalhes estratégicos só ao necessário. Quanto menos gente souber, menor a chance de vazar. Usem comunicação criptografada para discussões sensíveis - nunca em texto simples. Monitorem se informações internas aparecem em lugares públicos - às vezes o ataque é sutil, vazamento de informações para descreditar vocês. E tenham protocolo claro para lidar com tentativas de intimidação - porque vão tentar intimidar vocês. Não deixem isso passar sem resposta, mas respondam de forma estratégica e documentada.

---

## 10. Trabalho Remoto e Equipes Distribuídas

Organizações parceiras em ACPs frequentemente trabalham remotamente, o que adiciona camadas de complexidade à segurança. Quando pessoas estão em lugares diferentes, usando conexões diferentes, o controle fica mais difícil, mas não menos importante.

### 10.1. VPN e Conexões Seguras

Obriguem uso de VPN para acesso a recursos organizacionais. Redes Wi-Fi públicas por exemplo são terreno fértil para interceptação. Usem VPNs confiáveis que não sejam controladas por Big Techs, como ProtonVPN ou Mullvad. Configurem VPN em nível de roteador quando possível - assim todo o tráfego da organização passa por conexão segura. E monitorem conexões para padrões suspeitos - acessos de lugares inesperados ou em horários estranhos devem ser investigados.

### 10.2. Controle de Acesso

Implementem acesso baseado em papéis - nem todo mundo precisa acessar tudo. Quando alguém deixa o projeto, removam acesso imediatamente - não esperem, não deixem para depois. E usem logs para auditar acessos a recursos sensíveis - quando algo der errado, vocês vão precisar saber quem acessou o quê e quando. Para processos mais estruturados de revisão de permissões, consulte a seção 13.2 sobre auditorias de segurança.

### 10.3. Treinamento de Equipe

Realizem treinamentos regulares sobre segurança digital. É processo contínuo. Criem cultura de segurança dentro da organização, onde pessoas se sentem confortáveis em reportar preocupações. Estabeleçam canais para reportar preocupações de segurança sem medo de retaliação. E documentem políticas de segurança e tornem-nas acessíveis - ninguém pode seguir regras que não conhece.

### 10.4. Coordenação Entre Organizações

Estabeleçam protocolos de comunicação entre organizações parceiras. Quando várias organizações estão trabalhando juntas, o risco aumenta se não houver coordenação clara. Usem ferramentas seguras para coordenação - não WhatsApp, não Google Docs. Mantenham registro de decisões importantes em sistemas seguros - quando precisarem lembrar do que foi decidido meses depois, vocês vão agradecer. E revisem regularmente quem tem acesso a informações compartilhadas - pessoas mudam, projetos mudam, e o acesso precisa ser revisado.

---

## 11. Privacidade e Proteção de Dados Pessoais

Organizações precisam proteger não apenas informações estratégicas, mas também dados pessoais de membros da equipe e pessoas que interagem com a organização. A LGPD existe e, se vocês não estiverem preparados, pode dar problema. Mas mais importante do que a conformidade legal em si é a responsabilidade ética: vocês estão lidando com informações de pessoas que podem estar em situação vulnerável.

### 11.1. Minimização de Dados

O princípio da minimização é simples de entender, mas difícil de praticar: só coletem o que vocês realmente precisam. Não peçam CPF se vocês só precisam de e-mail. Não guardem endereço completo se vocês só precisam da cidade. E quando vocês não precisam mais daquele dado, deletem. Não deixem acumulando "por precaução". Dados que vocês não têm não podem vazar.

### 11.2. Consentimento e Transparência

Sobre consentimento, sejam transparentes desde o início. Expliquem claramente para que vocês precisam daquele dado, como vão usar e por quanto tempo vão guardar. E deixem claro que a pessoa pode pedir acesso ou exclusão dos próprios dados a qualquer momento. Isso não é só questão legal - é questão de respeito. Documentem consentimentos e políticas de privacidade, porque vocês vão precisar provar que obtiveram consentimento adequado se alguém questionar.

### 11.3. Proteção de Dados de Membros da Equipe

Dados de membros da equipe também precisam de proteção. Telefone, endereço, informações pessoais - nem todo mundo da organização precisa ter acesso a isso. Configurem permissões de acesso bem granulares. E quando vocês armazenam esses dados, criptografem. Principalmente se forem dados sensíveis como endereços físicos ou informações de saúde. Protejam informações de contato e endereços físicos especialmente, porque podem ser usados para doxxing ou outras formas de ataque.

### 11.4. Conformidade com LGPD

A LGPD pode parecer complicada, mas o básico não é tão difícil assim: vocês precisam de um processo para lidar com solicitações de pessoas que querem ver, corrigir ou deletar seus dados. Se vocês têm um volume grande de dados ou situações complexas, vale investir em consultoria jurídica. Mas comecem pelo básico: saibam o que vocês têm, onde está armazenado e como acessar se precisarem. Implementem medidas técnicas e organizacionais de proteção - não adianta ter política se não tem prática.

---

## 12. Planejamento de Contingência

A verdade é que coisas dão errado. E quando você está numa ACP contra Big Techs, precisa estar preparado se algo acontecer. Pode ser um vazamento de informações, uma conta comprometida, uma campanha de desinformação contra vocês ou até mesmo uma tentativa de intimidação.

### 12.1. Cenários de Risco

Identificar cenários de risco não é pessimismo - é realismo. Vocês estão se posicionando contra empresas bilionárias que têm interesse em ver vocês falharem. Isso não significa que vão acontecer, mas significa que vocês precisam estar preparados. Identifiquem e planejem para vazamento de informações estratégicas, comprometimento de contas ou sistemas, ataques de desinformação coordenados, intimidação ou ameaças a membros da equipe, e interrupção de serviços ou plataformas.

### 12.2. Plano de Continuidade

Para cada cenário que vocês identificarem, definam: quem vai fazer o quê? Quem toma as decisões? Como vocês vão se comunicar entre si? Como vão se comunicar publicamente? Ter isso documentado e acessível faz toda diferença quando o caos começa. Documentem processos críticos, identifiquem pontos únicos de falha, tenham alternativas para todas as ferramentas críticas, estabeleçam hierarquia de decisão em situações de crise, e mantenham contatos de emergência atualizados.

### 12.3. Backup e Recuperação

Backup é algo que todo mundo sabe que deveria fazer, mas pouca gente faz direito. E quando precisa, aí que descobrem que o backup estava corrompido, ou não tinha o arquivo certo, ou não conseguem restaurar. Façam backups regulares de todos os dados críticos - mensalmente no mínimo. E testem a restauração periodicamente. De que adianta ter backup se quando você precisa descobrir que não funciona? Mantenham backups em locais seguros e separados - pode ser outra organização parceira, pode ser em nuvem (em serviço seguro), pode ser até em HD físico que fica em outro endereço. E documentem procedimentos de recuperação - quando precisar, não dá tempo de pensar.

### 12.4. Comunicação de Crise

Comunicação durante crise também precisa ser planejada. Quem vai falar com a imprensa? Quem vai falar com outras organizações parceiras? Quem vai falar internamente com a equipe? Não pode ser todo mundo falando ao mesmo tempo, cada um no seu tom. Tenham plano de comunicação para situações de crise, identifiquem porta-vozes autorizados, preparem templates básicos que podem ser adaptados rapidamente. E mais importante: durante a crise, toda comunicação interna tem que ser em canais seguros. Se alguém está tentando sabotar vocês, não deem mais informações públicas do que o necessário.

---

## 13. Auditoria e Monitoramento

Segurança não é coisa que você configura uma vez e esquece. E parte importante desse processo é monitorar o que está acontecendo e revisar se as coisas ainda estão funcionando como deveriam.

### 13.1. Logs e Monitoramento

Logs podem parecer chato - só números e timestamps que ninguém lê. Mas quando algo dá errado, logs são o que permite entender o que aconteceu. Quem acessou o quê e quando? De onde veio o acesso? Que mudanças foram feitas? Sem logs, vocês estão voando às cegas. Ativem logs em todos os sistemas críticos, monitorem acessos a recursos sensíveis, configurem alertas para atividades suspeitas, e revisem logs regularmente - pode ser uma vez por semana, pode ser uma vez por mês, depende do volume. Mas não deixem acumular.

### 13.2. Auditorias de Segurança

Auditorias de segurança são como check-ups médicos - fazem sentido fazer periodicamente mesmo quando tudo parece estar funcionando. A cada três ou seis meses, façam uma revisão: as permissões de acesso ainda fazem sentido? As políticas de segurança estão sendo seguidas? Alguém mudou de função e ainda tem acesso a coisas que não precisa mais? Avaliem conformidade com políticas de segurança e testem as defesas através de exercícios simulados - descobrir problemas em exercício é muito melhor do que descobrir quando a coisa real acontece.

### 13.3. Revisão de Ferramentas

As ferramentas que vocês usam também precisam de revisão. Empresas mudam políticas de privacidade, mudam termos de serviço, são compradas por outras empresas. Aquela ferramenta que era segura há um ano pode não ser mais. Acompanhem essas mudanças. Avaliem regularmente se ferramentas em uso ainda são apropriadas, verifiquem se fornecedores mudaram políticas de privacidade, considerem alternativas se ferramentas se tornarem inseguras, e mantenham inventário atualizado de todas as ferramentas em uso. Se ninguém souber o que vocês têm, fica impossível proteger direito.

### 13.4. Melhorias Contínuas

Acompanhem notícias sobre segurança digital também. Vulnerabilidades são descobertas o tempo todo. Se uma ferramenta que vocês usam tem um problema conhecido, vocês precisam saber. E compartilhem conhecimento na equipe - se alguém descobre algo importante, não guardem só pra si. Segurança é esforço coletivo. Atualizem políticas com base em lições aprendidas, compartilhem conhecimento de segurança na equipe, e revisem e atualizem este manual regularmente. As coisas mudam, novas ameaças aparecem, novas ferramentas surgem. Um manual desatualizado pode ser até pior do que não ter manual nenhum, porque dá falsa sensação de segurança.

---

## 14. Ferramentas Recomendadas - Resumo

Esta seção resume as principais ferramentas recomendadas como alternativas seguras às plataformas das Big Techs. Esta é uma lista de referência rápida - para mais detalhes sobre cada ferramenta, consulte as seções anteriores.

**Comunicação por e-mail:** ProtonMail (proton.me), Tutanota (tutanota.com), Mailbox.org (mailbox.org)

**Mensagens instantâneas:** Signal (signal.org), Element/Matrix (element.io), Briar (briarproject.org)

**Videoconferência:** Jitsi Meet (meet.jit.si), BigBlueButton (bigbluebutton.org)

**Armazenamento em nuvem:** Nextcloud (nextcloud.com) - pode ser auto-hospedado, ProtonDrive (proton.me/drive), Tresorit (tresorit.com)

**Edição colaborativa:** CryptPad (cryptpad.fr), OnlyOffice (onlyoffice.com)

**VPN:** ProtonVPN (protonvpn.com), Mullvad (mullvad.net)

**Gerenciadores de senhas:** Bitwarden (bitwarden.com), KeePass (keepass.info)

**Criptografia:** VeraCrypt (veracrypt.fr) para criptografia de disco, GPG (gnupg.org) para criptografia de e-mail

**Sistemas operacionais:** Linux (distribuições: Ubuntu, Debian, Fedora), LineageOS (lineageos.org) para Android

**Navegadores:** Firefox (firefox.com), Tor Browser (torproject.org) para anonimato máximo

---

## 15. Checklist de Segurança Organizacional

Use este checklist para avaliar a segurança da sua organização:

- [ ] Todos os membros da equipe têm autenticação em dois fatores ativada
- [ ] Usamos ferramentas alternativas às plataformas das Ré para comunicação interna
- [ ] Documentos sensíveis da ACP estão criptografados e em plataformas seguras
- [ ] Temos política de senhas forte e gerenciador de senhas implementado
- [ ] Realizamos backups regulares e testamos restauração
- [ ] Temos plano de resposta a incidentes documentado
- [ ] Todos os dispositivos organizacionais estão criptografados
- [ ] Usamos VPN para acesso remoto a recursos organizacionais
- [ ] Limitamos acesso a informações sensíveis baseado em necessidade
- [ ] Revimos regularmente permissões de acesso
- [ ] Treinamos equipe sobre segurança digital regularmente
- [ ] Temos protocolo para comunicação segura entre organizações parceiras
- [ ] Não usamos Google Drive, Gmail ou WhatsApp para assuntos da ACP
- [ ] Monitoramos menções à organização online
- [ ] Temos plano de continuidade documentado

---

## 16. Considerações Finais

A segurança digital organizacional em contextos de advocacy e ações legais contra Big Techs não é opcional - é uma necessidade estratégica. As empresas contra as quais vocês estão lutando têm recursos massivos, capacidade de vigilância e histórico de interferência em processos que as afetam.

Usar as plataformas dessas empresas para coordenar ações contra elas é como discutir estratégias de guerra no acampamento do inimigo. As alternativas existem, são viáveis e, em muitos casos, superiores em termos de privacidade e controle. Sim, algumas têm curva de aprendizado. Sim, algumas precisam de mais configuração. Mas também sim: vocês conseguem usar. Já vimos organizações menores e maiores implementando essas ferramentas com sucesso.

Como dissemos, segurança não é algo que você faz uma vez e pronto. Vai ter que revisar práticas, atualizar ferramentas, treinar equipe, se adaptar a novos riscos. Mas não precisa fazer tudo de uma vez. Comecem pelo essencial - comunicação segura, armazenamento seguro, senhas fortes - e vão melhorando aos poucos.

O mais importante: vocês não estão protegendo apenas informações. Vocês estão protegendo causas, pessoas, a possibilidade de fazer justiça. Cada documento vazado, cada conta hackeada, cada estratégia exposta não é só um problema técnico - é um golpe no trabalho de vocês, nas pessoas que vocês representam, na capacidade de vocês continuarem fazendo o que fazem.

Este manual é um ponto de partida, não um manual definitivo. Adaptem às realidades de vocês. Compartilhem conhecimento com outras organizações parceiras - vocês estão nisso juntos. E não deixem o perfeito ser inimigo do bom: melhor começar com algumas práticas básicas do que não fazer nada porque parece difícil demais.

A resistência começa com informação, com ação, mas também começa com proteção. Proteção de vocês, proteção das informações, proteção das causas. Cuidem-se.

---

## 17. Glossário

**Autenticação em Dois Fatores (2FA):** Método de segurança que exige duas etapas para acessar uma conta. Além da senha, o usuário precisa fornecer um código gerado por um aplicativo ou enviado para outro dispositivo.

**Big Techs:** Grandes empresas de tecnologia que dominam o mercado digital, incluindo Meta (Facebook/Instagram/WhatsApp), Google (YouTube/Gmail), X (Twitter) e ByteDance (TikTok).

**Criptografia de Ponta a Ponta:** Tecnologia que protege os dados em trânsito, garantindo que apenas o remetente e o destinatário possam acessá-los, mesmo a plataforma não consegue decifrar.

**Doxxing:** Prática de coletar e divulgar informações pessoais de alguém sem consentimento, frequentemente com a intenção de intimidar ou expor publicamente.

**End-to-End Encryption (E2EE):** Ver Criptografia de Ponta a Ponta.

**Gerenciador de Senhas:** Ferramenta que cria e armazena senhas fortes e únicas para cada conta, facilitando a gestão segura dessas informações.

**LGPD:** Lei Geral de Proteção de Dados (Lei nº 13.709/2018), que estabelece regras sobre coleta, armazenamento e uso de dados pessoais no Brasil.

**Phishing:** Ataque que usa e-mails, mensagens ou sites falsos para enganar usuários e roubar informações sensíveis, como senhas ou dados bancários.

**VPN (Virtual Private Network):** Rede privada virtual que criptografa a conexão do usuário, ocultando sua localização e protegendo seus dados durante a navegação.

**Vulnerabilidade:** Falha ou fraqueza em sistemas, dispositivos ou softwares que podem ser explorados por atacantes para realizar invasões ou roubo de informações.

---

## 18. Guias Práticos e Recursos Adicionais

### 18.1. Guia Passo a Passo para Configuração de VPN

Para configurar uma VPN em sua organização:

1. Escolha um serviço de VPN confiável que não seja controlado por Big Techs (recomendamos ProtonVPN ou Mullvad - veja seção 14).
2. Baixe o aplicativo no dispositivo (PC, smartphone, tablet).
3. Instale e abra o aplicativo.
4. Crie uma conta ou faça login no serviço.
5. Escolha uma localização de servidor (geralmente, um país onde a conexão seja segura).
6. Clique em "Conectar". O tráfego da sua internet será criptografado automaticamente.
7. Ative a conexão VPN sempre que usar redes Wi-Fi públicas ou precisar de maior privacidade.

Para mais informações sobre VPN, consulte a seção 10.1.

### 18.2. Guia Passo a Passo para Gerenciadores de Senhas

Para implementar gerenciador de senhas na organização:

1. Escolha um gerenciador de senhas confiável (recomendamos Bitwarden ou KeePass - veja seção 8.1).
2. Baixe o aplicativo ou acesse a versão online.
3. Crie uma conta com uma senha mestra forte (a única que você precisará memorizar).
4. Importe ou insira manualmente suas senhas nas categorias fornecidas.
5. Use o gerador de senhas do aplicativo para criar combinações fortes e únicas para novas contas.
6. Ative a sincronização entre dispositivos para acessar suas senhas em qualquer lugar.
7. Atualize suas senhas regularmente e exclua contas antigas ou não utilizadas.

Para mais informações sobre senhas e autenticação, consulte a seção 8.

### 18.3. Organizações de Apoio

**SaferNet Brasil:** oferece suporte jurídico e técnico para crimes digitais. Disponível em [safernet.org.br](https://safernet.org.br)

**Access Now:** fornece assistência técnica em segurança digital para ativistas. Digital Security Helpline oferece ajuda direta para ataques digitais. Disponível em [accessnow.org](https://accessnow.org)

**Tactical Tech:** disponibiliza guias gratuitos sobre privacidade e segurança online. Disponível em [tacticaltech.org](https://tacticaltech.org)

**EFF (Electronic Frontier Foundation):** atua na defesa de direitos digitais e oferece o Guia de Autodefesa Contra Vigilância. Disponível em [eff.org](https://eff.org)

### 18.4. Documentação Técnica Recomendada

- **Guia de Autodefesa Contra Vigilância (EFF):** guia completo sobre privacidade e segurança digital, disponível em [eff.org/pt-br/ssd](https://ssd.eff.org/pt-br)

- **Security in-a-box (Tactical Tech):** conjunto de guias práticos sobre segurança digital, disponível em [securityinabox.org](https://securityinabox.org)

- **Prism Break:** lista de alternativas a serviços que praticam vigilância em massa, disponível em [prism-break.org](https://prism-break.org)

### 18.5. Legislação Relevante

- **Lei Geral de Proteção de Dados (LGPD - Lei nº 13.709/2018):** estabelece regras sobre coleta, armazenamento e uso de dados pessoais no Brasil.

- **Marco Civil da Internet (Lei nº 12.965/2014):** estabelece princípios, garantias, direitos e deveres para o uso da internet no Brasil.

- **Lei de Ação Civil Pública (Lei nº 7.347/85):** disciplina a ação civil pública para proteção de interesses difusos e coletivos.

- **Código de Defesa do Consumidor (Lei nº 8.078/90):** estabelece normas de proteção e defesa do consumidor.

---

**Código Não Binário**  
www.codigonaobinario.org  
contato@codigonaobinario.org

Este manual é um documento vivo. Contribuições e atualizações são bem-vindas.