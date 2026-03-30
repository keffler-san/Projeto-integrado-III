# Projeto-integrado-III
projeto do trabalho da faculdade
Tema: Política de Segurança da Informação (PSI) completa para Empresa Fictícia
Grupo: Elias/Dev. e Marcos/CEO 
Descrição do projeto: criar uma PSI para a segurança da informação dos envolvidos na empresa buscando confiança e privacidade dos nossos colaboradores e regularidades legais.
Plano inicial: estudar as politicas de segurança de dados legais ja existente e implementar mais de acordo com a necessidade do projeto
Nome da empresa: Securewave
descricao da empresa:uma empresa de protecao de dados
foco do projeto: desenvolver um conjunto de regra para uma protecao de dados do cliente e da enpresa contratante estudando lei ja existente,regras de outras empresas, e prioridades de nessessidades operamentais
escopo:regars como lgpd e psi ja existentes
nao inclui regras de funcionamento da empresa como horario de entrada e saida ou quantidade de dias trabalhados 

Parte 2

A Securewave é uma empresa especializada em proteção de dados, e o objetivo deste projeto é desenvolver uma Política de Segurança da Informação (PSI) que garanta a confidencialidade, integridade e disponibilidade das informações de clientes e colaboradores. A PSI da Securewave tem como foco principal a proteção de dados sensíveis e a promoção da confiança e privacidade de todos os envolvidos, além de assegurar a conformidade com a LGPD e outras normas de boas práticas de segurança.

Esta política define regras claras sobre controle de acesso, criptografia, backup e descarte seguro de informações, garantindo que apenas pessoas autorizadas possam acessar os dados conforme suas funções. Além disso, a PSI estabelece procedimentos de gestão de incidentes, permitindo identificar, registrar e responder rapidamente a qualquer falha de segurança. Todos os colaboradores têm responsabilidades definidas e passam por treinamentos periódicos para assegurar a adoção das melhores práticas de proteção de dados.

A política também inclui monitoramento contínuo e auditorias periódicas, para garantir que a Securewave esteja sempre alinhada às normas legais e aos padrões internacionais de segurança, como a ISO/IEC 27001. Revisões regulares da PSI são realizadas para incorporar novas regulamentações ou melhorias operacionais, mantendo a política atualizada e eficaz. Com essas medidas, a Securewave assegura a proteção das informações de clientes e da própria empresa, fortalecendo a confiança e promovendo um ambiente seguro e confiável para todos os envolvidos.

Artefatos: 
Requisitos Funcionais (RF)

RF1 – Controle de Acesso

Descrição: O sistema deve permitir que apenas usuários autorizados tenham acesso aos dados, com diferentes níveis de permissão conforme função.
Critério de Aceitação: Usuários sem autorização não conseguem acessar dados confidenciais; os administradores conseguem gerenciar níveis de permissão.

RF2 – Criptografia de Dados

Descrição: Todos os dados sensíveis devem ser criptografados durante armazenamento e transmissão.
Critério de Aceitação: Testes de auditoria confirmam que dados armazenados e transmitidos não podem ser lidos sem a chave de criptografia.

RF3 – Gestão de Incidentes

Descrição: O sistema deve registrar, notificar e permitir a resposta a incidentes de segurança.
Critério de Aceitação: Todo incidente de segurança gera um registro no sistema e uma notificação automática à equipe responsável, dentro do prazo definido.

RF4 – Backup e Recuperação

Descrição: O sistema deve realizar backups periódicos e permitir a recuperação completa de dados em caso de falha ou ataque.
Critério de Aceitação: Em testes de restauração, 100% dos dados críticos são recuperados em até o tempo máximo definido no plano de contingência.
Requisitos Não Funcionais (RNF)

RNF1 – Conformidade Legal

Descrição: A PSI e os sistemas devem cumprir todas as exigências da LGPD e normas de boas práticas de segurança (ISO/IEC 27001).
Critério de Aceitação: Auditoria legal comprova que todos os processos de tratamento de dados estão em conformidade com a LGPD.

RNF2 – Disponibilidade

Descrição: Os sistemas críticos da empresa devem estar disponíveis para uso autorizado pelo menos 99% do tempo.
Critério de Aceitação: Monitoramento do sistema confirma que a disponibilidade é mantida dentro do SLA definido, sem interrupções não planejadas acima de 1% do tempo.

RNF3 – Treinamento e Capacitação

Descrição: Todos os colaboradores devem receber treinamento periódico sobre boas práticas de segurança da informação.
Critério de Aceitação: 100% dos colaboradores concluem o treinamento anual e passam em avaliação de conhecimento mínimo sobre segurança da informação.
