# Projeto Circuitos Digitais - Respiradores

Projeto final da matéria Circuitos Digitais UNIFESP - São José dos Campos

# Sistema Digital de Detecção de Vazamento em Respiradores Mecânicos
O circuito desenvolvido simula o funcionamento de um módulo de segurança acoplado a respiradores mecânicos, para identificação de possíveis vazamentos no circuito de ar do equipamento. Para isso, o sistema conta com três sensores integrados:

Sensor de Pressão
Sensor de Fluxo de Ar
Sensor de Temperatura

O usuário pode definir os limiares considerados ideais para a ventilação assistida. A partir disso, o circuito compara em tempo real os dados recebidos pelos sensores com esses valores de referência.

Sempre que alguma variável (como a pressão, o fluxo ou a temperatura) sair da faixa segura, o sistema reage de forma autônoma:

Acionando alertas visuais

Exibindo a diferença se comparado ao referencial no display de 7 segmentos, indicando a instabilidade

Para isso, implementamos comparadores lógicos, subtrator binário, registradores com flip-flops tipo D para armazenar valores anteriores, e portas lógicas (OR) para tomada de decisão combinada. A simulação foi realizada no WiredPanda, e o circuito foi validado funcionalmente com base nos critérios estabelecidos pela lógica digital.

# Vídeo de apresentação da ideia (Pitch acadêmico):

# Vídeo do circuito completo (mostrando e explicando o circuito no panda)
https://drive.google.com/file/d/1FhT8555XfPAVtedlRrl8_pKMKKbHzodD/view?usp=sharing

# Detalhes
O projeto foi todo feito utilizando o software WiRedPanda na versão 4.1.12 . Tentamos deixar o mais bem explicado possível e com todos os circuitos separados de maneira que possam ser utilizados em outros projetos, tendo em vista que não encontramos nada disponível e de fácil acesso na internet ou aqui no github.

# Integrantes
Joana Carla Castro Gomes

