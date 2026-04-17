🚦 Arduino Traffic Light Control

Este é um projeto simples utilizando Arduino para simular um semáforo com LEDs, com dois modos de funcionamento:

- 🔁 Modo automático: troca as luzes a cada 5 segundos
- 🎮 Modo manual (Serial): controle via teclado usando o Monitor Serial

---

🛠️ Tecnologias utilizadas

- Arduino UNO
- Linguagem C/C++ (Arduino)
- Comunicação Serial

---

⚙️ Funcionamento

O sistema controla três LEDs:

- 🔴 Vermelho
- 🟡 Amarelo
- 🟢 Verde

🔁 Modo automático

O semáforo alterna automaticamente entre as cores com um intervalo de 5 segundos.

🎮 Modo manual (Serial)

Você pode controlar o semáforo pelo Monitor Serial da IDE Arduino:

Tecla| Ação
R| Liga o LED vermelho
Y| Liga o LED amarelo
G| Liga o LED verde
A| Ativa o modo automático

---

🔌 Montagem do circuito

Cada LED está conectado a um pino digital do Arduino com um resistor (≈200Ω ou 220Ω) para limitar a corrente.

Estrutura básica:

Pino digital → LED → Resistor → GND

---

💻 Código

O código utiliza:

- "pinMode()" para definir os pinos como saída
- "digitalWrite()" para ligar/desligar LEDs
- "Serial.begin()" para iniciar comunicação
- "Serial.read()" para receber comandos

---

🚀 Como usar

1. Conecte o Arduino ao computador
2. Faça o upload do código
3. Abra o Monitor Serial
4. Configure para 9600 baud
5. Coloque em "Sem quebra de linha"
6. Digite os comandos (R, Y, G, A)

---

📚 Objetivo do projeto

Este projeto foi desenvolvido com o objetivo de aprender:

- Controle de pinos digitais
- Uso de LEDs com resistores
- Comunicação serial com o Arduino
- Lógica de programação aplicada

---

🔥 Possíveis melhorias

- Adicionar botão físico para controle
- Criar interface com aplicativo ou Bluetooth
- Ajustar tempo do semáforo dinamicamente
- Implementar sensores

---

👨‍💻 Autor

Projeto desenvolvido por Wagner 🚀