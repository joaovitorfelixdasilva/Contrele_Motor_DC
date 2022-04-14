Trabalho desenvolvido com intuíto de funcionamento total de um Controlador de velocidade e temporização de mototr DC.

Para ser efetuado, precisaremos de alguns componentes:

 *Display: Utilizaremos um [display 16x2](https://components101.com/displays/16x2-lcd-pinout-datasheet) onde existem 16 colunas e 2 linhas para escrita, esse modelo apresenta fundo azul e letras brancas e será utlizado para mostrar a função que deverá ser aplicada no motor.

*Motor: Para o motor, será utilizado um [motor DC](https://recursos.techmakers.com.br/MediaCenter/Datasheet%20Micro%20Motor%20DC%2012V%206500RPM%20P-N-AK555-306PL12S6500C.pdf), mas conhecido como Motor de corrente contínua, onde a velocidade do motor é controlada através da variação da corrente, diferente de outros modelos.

*Mosfet: O [mosfet](https://flaviobabos.com.br/mosfet/****) é um transistor de efeito de campo de semicondutor de óxido metálico, e será utilizado para a transmissão da tensão para o motor.

*Teclado: Será utilizado um [teclado 4x4](https://cdn.sparkfun.com/assets/f/f/a/5/0/DS-16038.pdf), bastante utilizado para Arduino, é ligado diretamente a placa, no teclado cada tecla acionará uma função diferente para o motor de acordo com a tecla pressionada.

*Fonte externa: utilizaremos uma fonte para energizar o circuito a partir das placas

Precisaremos utilizar duas placas que foram efetuadas durante o curso para o funcionamento do projeto.

*[PiCKIT 2](https://www.google.com/url?sa=i&url=http%3A%2F%2Felectronics-diy.com%2Felectronic_schematic.php%3Fid%3D824&psig=AOvVaw0fKVQ5oa-WGl_pJipMtp1v&ust=1650021809616000&source=images&cd=vfe&ved=0CAkQjRxqFwoTCOCHybG4k_cCFQAAAAAdAAAAABAO): Sua função será transmitir oa dados do arquivo no computador para o PIC16F887.  
*[PICKIT16F887](https://www.utmel.com/components/pic16f887-8-bit-microcontroller-programming-datasheet-and-pinout?id=777): Após receber os dados do PICKIT 2 ele transmitirá os dados diretamente ao display, ocasionando o controle e funcionamento do projeto.

*Saída PWM: O [PWM](https://www.citisystems.com.br/pwm/#:~:text=PWM%20%C3%A9%20a%20t%C3%A9cnica%20usada,a%20gera%C3%A7%C3%A3o%20de%20sinais%20PWM.) é uma técnica utilizada para gerar sinais analógicos de um dispositivo digital (Microcontrolador no nosso caso) ele é tão eficiente que hoje em dia quase todos os Microcontroladores modernos possuem hardware dedicado para a geração de sinais PWM.

Temos como objetivo de projeto, criar um protótipo onde a programação feita nos computadores possa ser utilizada adequadamente, e que a cada tecla pressionada tenha a sua devida ação ao display e também para o motor de corrente contínua, tendo um projeto totalmente funcional efetuado com total êxito. Além disso o grupo espera poder ter maior aprofundamento em todas as etapas do projeto, contando com o protótipo ou a programação pelo software, assim conseguindo as realizar com maior facilidade e ganhando um maior conhecimento sobre a matéria de eletrônica.

Desenvolvimento:

















