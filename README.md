# robocar-racer-controller-2025
Visão Geral
Este repositório contém o projeto de hardware da placa controladora desenvolvida pela Equipe Laser para a competição Robocar Racer 2025. A placa recebe e interpreta dados da Raspberry Pi para controlar o motor brushless (ESC) e o servo motor, implementando isolamento galvânico e redundância via rádio controle.

Visualização do Projeto
Modelo 3D
Documentação Técnica (PDF)
Para detalhes de roteamento e conexões, acesse os ficheiros abaixo:

📄 Esquemático Completo

📄 Layout da PCB

📦 Modelo 3D Interativo (GLB)

Especificações Técnicas
Microcontrolador: ESP32 (NodeMCU/DevKit V1)

Software de EDA: KiCad 8.0.6

Dimensões da PCB: 91.00 mm x 67.75 mm

Isolamento: Optoacopladores PC817 (Separação entre lógica/USB e potência/Bateria).

Operação e Segurança
O sistema gerencia a tração e direção do veículo em três estados:

Modo Autônomo: Controle via Raspberry Pi (Serial/USB).

Modo Manual (Radio): Redundância via rádio controle externo.

Modo Neutro: Veículo parado por segurança.

Interfaces de Hardware
Barramento GY-87: Conexão I2C para IMU (Telemetria e estabilização).

Feedback Visual: 4 LEDs (Power, Estado 1, Estado 2, Estado 3).

Isolamento de Terra: Separação física entre GND_CAR e Earth (GND lógico).

Estrutura do Repositório
/Gerber: Arquivos finais de fabricação.

/Assets: Fotos, modelos 3D e documentação em PDF.

/Meus footprints.pretty: Biblioteca de footprints customizados.

Car_v1.kicad_...: Arquivos fonte do projeto KiCad.
