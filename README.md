Triagem Médica de Pacientes

Este programa foi desenvolvido para realizar a triagem de pacientes com sintomas comuns como febre, dor no corpo e vômitos. Ele coleta informações sobre os sintomas apresentados pelo paciente e calcula a gravidade da condição. Ao final, o sistema gera uma ficha médica detalhada com as informações do paciente e um número de chamada para auxiliar na organização do atendimento médico.

Objetivo

O objetivo deste programa é automatizar o processo inicial de triagem, facilitando a classificação da gravidade dos sintomas e ajudando a orientar as próximas ações médicas de forma eficiente.

Como o Programa Funciona

Coleta de Informações Pessoais

O programa começa coletando informações pessoais do paciente, como nome completo, CPF e idade. Essas informações são importantes para gerar uma ficha médica identificável e organizar o atendimento.

Triagem de Sintomas Em seguida, o paciente responde a uma série de perguntas relacionadas aos sintomas que está apresentando. O sistema verifica sinais de febre, dor no corpo, vômitos e outros sintomas. Para cada sintoma informado, o sistema atribui um valor de gravidade à condição do paciente.

- Febre: O sistema pergunta se o paciente tem febre e qual foi a temperatura mais alta registrada. Caso a temperatura esteja acima de 39°C, um ponto de gravidade mais alto é atribuído.

- Dor no Corpo: O programa questiona se o paciente sente dores e, caso a resposta seja afirmativa, pede informações sobre a localização da dor (como no peito ou cabeça) e a intensidade da dor (em uma escala de 0 a 10). Se a dor for intensa ou localizada em áreas mais críticas (como o peito), isso aumenta a gravidade.

- Vômitos: Caso o paciente tenha apresentado episódios de vômitos, o sistema também aumenta a gravidade da condição.

Cálculo da Gravidade

A gravidade dos sintomas é calculada somando os pontos atribuídos a cada resposta. Com base na pontuação total, o sistema classifica a gravidade do quadro médico do paciente em três categorias:

- Leve: Quando o número total de pontos é 4 ou menos.

- Moderada: Quando o número de pontos fica entre 5 e 7.

- Grave: Quando a pontuação é superior a 7.

Geração da Ficha Médica

Após coletar todas as informações, o programa gera uma ficha médica detalhada, contendo os dados pessoais do paciente, os sintomas reportados, a gravidade do quadro e o número de chamada gerado aleatoriamente.

A ficha médica inclui:

- Nome do paciente

- CPF

- Idade

- Pressão (se foi mencionada)

- Sintomas relacionados à febre, dor no corpo e vômitos

- Data de início dos sintomas

- Motivo da dor (se disponível)

- Classificação da gravidade do quadro

Exibição da Ficha Médica

O programa exibe a ficha médica na tela, incluindo todos os dados coletados e um número de chamada aleatório, o que pode simular a organização do atendimento no hospital.

Estrutura do Código

O código é organizado em várias funções para facilitar a execução de cada parte do processo de triagem:

- Função pergunta_febre() Esta função lida com as perguntas relacionadas à febre. Ela pergunta se o paciente tem febre e, caso afirmativo, coleta a temperatura mais alta registrada. Com base na temperatura, ela aumenta o contador de gravidade, se necessário.

- Função pergunta_sintomas() Aqui, são feitas perguntas sobre a dor no corpo e os vômitos. A função verifica se a dor está localizada em áreas mais críticas (como peito ou cabeça) e se a dor é intensa. Além disso, também pergunta sobre o motivo da dor (se conhecido) e a intensidade, além de verificar se houve episódios de vômito.

- Função triagem() Esta é a função principal que orquestra todo o processo. Ela coleta as informações pessoais do paciente, chama as funções pergunta_febre() e pergunta_sintomas() para coletar os dados relacionados aos sintomas e calcula a gravidade total com base nas respostas. Ela também gera e organiza todos os dados na ficha médica do paciente.

- Função exibir_ficha() Depois de gerar a ficha médica, essa função é responsável por exibir todas as informações do paciente de maneira organizada na tela, incluindo um número de chamada gerado aleatoriamente.

Como Usar

Execute o programa: Ao rodar o script, o programa pedirá que você insira as informações do paciente, uma por uma.

- Responda às perguntas: O sistema fará perguntas sobre os sintomas do paciente (febre, dor, vômito, etc.). Responda a cada pergunta com base nos sintomas apresentados pelo paciente.

- Receba a ficha médica: Após coletar todos os dados e calcular a gravidade dos sintomas, o programa exibirá a ficha médica gerada, incluindo a classificação de gravidade e um número de chamada.

Requisitos

- Python 3.x: O programa foi desenvolvido usando Python e não possui dependências externas.
Grupo

Integrantes: 

Matheus Machado Caposse, Caio Berardo de Araujo, Henrique Pacifico  
