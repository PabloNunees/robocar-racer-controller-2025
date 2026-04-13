# Minha Biblioteca de Footprints

Esta pasta contém os footprints customizados que eu desenvolvi para o projeto **Robocar Racer 2025**. 

## Sobre a Biblioteca
Criei estes componentes para suprir a falta de modelos nas bibliotecas padrão do KiCad e para otimizar o design da placa. Os footprints foram ajustados para garantir precisão na furação e facilitar o processo de montagem e soldagem.

### O que você encontrará aqui:
* Modelos de conectores específicos utilizados no veículo.
* Pads otimizados para componentes de potência.
* Footprints de módulos (ESP32, GY-87, etc.) validados para este projeto.

## Configuração no KiCad
Para que o projeto abra sem erros de componentes ausentes, adicione esta pasta às bibliotecas do seu KiCad:
1. Acesse **Preferences** > **Manage Footprint Libraries**.
2. Na aba **Project Specific Libraries**, adicione o caminho desta pasta (`Meus footprints.pretty`).

**Nota:** Estes arquivos são parte integrante do layout da PCB. Qualquer alteração nos arquivos `.kicad_mod` desta pasta afetará diretamente o posicionamento e a integridade do projeto final.
