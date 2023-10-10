# BONECA-BATATINHA
**Descrição do Projeto**

Este projeto, concebido pelo Professor Thiago Antonio Marcão, apresenta uma boneca articulada com trena digital, proporcionando uma experiência única e funcional. A combinação de componentes, incluindo dois motores DC controlados por relé, servo motores, um display OLED e um sensor ultrassônico, demonstra uma integração cuidadosa para criar uma boneca interativa.

**Componentes:**
1. **Servo Motores (3x):** Esses servo motores controlam a articulação da boneca, garantindo movimentos suaves e precisos.
2. **Display OLED:** O display OLED (U8g2) exibe informações visuais, incluindo o texto "BATATINHA" e a distância medida em centímetros.
3. **Sensor Ultrassônico:** Responsável por medir a distância entre a boneca e objetos ao seu redor.
4. **Buzzer:** Emite um som de aviso quando algo está próximo da boneca.
5. **Relé:** Controla a ativação e desativação de dispositivos elétricos. No caso específico, o relé controla dois motores DC, proporcionando movimentos adicionais à boneca.

**Bibliotecas Utilizadas:**
1. **Servo.h:** Facilita o controle de servo motores.
2. **U8g2lib.h:** Utilizada para dispositivos de exibição, neste caso, o display OLED.

**Funcionalidades Principais:**
- A boneca mede a distância usando o sensor ultrassônico.
- O display OLED exibe a palavra "BATATINHA" e a distância medida.
- Quando a distância é menor ou igual a 30 cm, a boneca emite um som de aviso, aciona dois motores DC controlados pelo relé e move os servo motores para uma posição específica.
- Após 3 segundos, o relé desliga o buzzer, desativa os motores DC e retorna os servo motores à posição inicial.

Esse projeto engloba interatividade e medição de distância, destacando-se pela inclusão de motores DC controlados pelo relé para movimentos adicionais da boneca. A integração harmoniosa dos componentes e bibliotecas contribui para uma experiência envolvente e educativa.
