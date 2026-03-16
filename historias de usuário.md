# UpFit --- Histórias de Usuário (User Stories)

# 1. Autenticação e Perfil

## US01 --- Cadastro de usuário

**Como** um novo usuário\
**Eu quero** criar uma conta no aplicativo\
**Para** começar a registrar meus treinos e acompanhar minha evolução.

### Critérios de Aceitação

-   O usuário deve informar email e senha.
-   O sistema deve validar se o email já está cadastrado.
-   Após cadastro, o usuário deve conseguir acessar a plataforma.

------------------------------------------------------------------------

## US02 --- Login no sistema

**Como** um usuário cadastrado\
**Eu quero** fazer login na plataforma\
**Para** acessar meu progresso e minhas conquistas.

### Critérios de Aceitação

-   O sistema deve validar credenciais.
-   O sistema deve permitir acesso ao dashboard após login válido.

------------------------------------------------------------------------

## US03 --- Criar avatar

**Como** um usuário iniciante\
**Eu quero** criar ou personalizar um avatar\
**Para** representar minha evolução dentro do sistema gamificado.

------------------------------------------------------------------------

## US04 --- Editar perfil

**Como** um usuário\
**Eu quero** editar minhas informações pessoais\
**Para** manter meus dados atualizados.

------------------------------------------------------------------------

# 2. Registro de Treinos

## US05 --- Registrar check-in de treino

**Como** um usuário\
**Eu quero** registrar um check-in após realizar um treino\
**Para** ganhar XP e avançar no sistema de progressão.

### Critérios de Aceitação

-   O usuário deve estar autenticado.
-   O sistema deve registrar data e tipo de treino.
-   O sistema deve enviar evento para cálculo de XP.

------------------------------------------------------------------------

## US06 --- Registrar tipo de atividade

**Como** um usuário\
**Eu quero** informar o tipo de treino realizado (corrida ou
musculação)\
**Para** acompanhar minha consistência nas atividades físicas.

------------------------------------------------------------------------

## US07 --- Visualizar histórico de treinos

**Como** um usuário\
**Eu quero** visualizar o histórico dos meus treinos\
**Para** acompanhar minha frequência ao longo do tempo.

------------------------------------------------------------------------

# 3. Sistema de Progressão (Gamificação)

## US08 --- Ganhar XP por treino

**Como** um usuário\
**Eu quero** receber pontos de experiência (XP) ao registrar um treino\
**Para** evoluir meu nível dentro da plataforma.

------------------------------------------------------------------------

## US09 --- Evoluir de nível

**Como** um usuário\
**Eu quero** subir de nível conforme acumulo XP\
**Para** sentir progresso e motivação para continuar treinando.

------------------------------------------------------------------------

## US10 --- Desbloquear recompensas

**Como** um usuário\
**Eu quero** desbloquear itens, badges ou conquistas ao atingir níveis\
**Para** visualizar meu progresso de forma recompensadora.

------------------------------------------------------------------------

# 4. Desafios e Streaks

## US11 --- Participar de desafios

**Como** um usuário\
**Eu quero** participar de desafios semanais ou mensais\
**Para** me manter motivado a treinar regularmente.

------------------------------------------------------------------------

## US12 --- Manter streak de treinos

**Como** um usuário\
**Eu quero** acumular uma sequência (streak) de dias treinando\
**Para** reforçar o hábito de atividade física.

------------------------------------------------------------------------

## US13 --- Receber recompensa por streak

**Como** um usuário\
**Eu quero** ganhar recompensas por manter uma sequência de treinos\
**Para** me incentivar a não interromper minha rotina.

------------------------------------------------------------------------

# 5. Guildas e Social

## US14 --- Criar guilda

**Como** um usuário\
**Eu quero** criar uma guilda\
**Para** treinar com amigos e participar de desafios coletivos.

------------------------------------------------------------------------

## US15 --- Entrar em uma guilda

**Como** um usuário\
**Eu quero** entrar em uma guilda existente\
**Para** fazer parte de uma comunidade com objetivos semelhantes.

------------------------------------------------------------------------

## US16 --- Visualizar ranking da guilda

**Como** um usuário\
**Eu quero** visualizar o ranking de membros da minha guilda\
**Para** acompanhar quem está mais ativo no grupo.

------------------------------------------------------------------------

## US17 --- Participar de desafios de guilda

**Como** um usuário\
**Eu quero** participar de desafios coletivos da guilda\
**Para** colaborar com o progresso do grupo.

------------------------------------------------------------------------

# 6. Feed Social

## US18 --- Visualizar atividade de amigos

**Como** um usuário\
**Eu quero** visualizar os treinos e conquistas dos meus amigos\
**Para** me sentir motivado a continuar treinando.

------------------------------------------------------------------------

## US19 --- Compartilhar conquistas

**Como** um usuário\
**Eu quero** compartilhar minhas conquistas no feed\
**Para** mostrar meu progresso e motivar outros usuários.

------------------------------------------------------------------------

# 7. Monetização (Freemium)

## US20 --- Assinar plano premium

**Como** um usuário\
**Eu quero** assinar um plano premium\
**Para** acessar funcionalidades avançadas da plataforma.

------------------------------------------------------------------------

# Organização por Microserviços

  Microserviço   Histórias Relacionadas
  -------------- ------------------------
  Autenticação   US01, US02
  Perfil         US03, US04
  Treinos        US05, US06, US07
  Progressão     US08, US09, US10
  Desafios       US11, US12, US13
  Guildas        US14, US15, US16, US17
  Social         US18, US19
  Monetização    US20

------------------------------------------------------------------------
