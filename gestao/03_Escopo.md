# 3. Escopo


O projeto tem como objetivo o desenvolvimento de um sistema de monitoramento de vibração e temperatura em motores elétricos, com foco na detecção precoce de anomalias para auxiliar na manutenção preventiva. O sistema será composto por hardware e software, integrando sensores, comunicação sem fio e uma interface gráfica para visualização e análise dos dados.

# Objetivos Específicos:

 ## Desenvolvimento do Dispositivo de Aquisição de Dados:

- Projeto e implementação de um dispositivo para coleta de dados em tempo real.

- Utilização de sensores de vibração (acelerômetro) e temperatura para monitoramento contínuo do motor.

- Garantir a precisão das leituras para análise posterior.

- Comunicação via ESP32:

- Implementar a comunicação sem fio utilizando o microcontrolador ESP32.

- Estabelecer a transmissão dos dados adquiridos para um sistema de processamento.

- Garantir a estabilidade e integridade dos dados durante a comunicação.

## Desenvolvimento da Interface Gráfica:

- Criar uma interface amigável para a visualização em tempo real das informações coletadas.

- Exibir gráficos de vibração e temperatura em tempo real.

- Fornecer alertas em caso de valores anômalos que indiquem possíveis falhas.

## Análise de Dados e Detecção de Necessidade de Manutenção Preditiva:

- Implementar algoritmos para análise dos dados coletados (Business Intelligence – BI).

- Detectar tendências que possam indicar desgaste ou falha iminente no motor.

- Registrar históricos para facilitar a análise preditiva e a tomada de decisão.

## Testes e Validação em Ambiente Controlado:

- Realizar testes em ambiente controlado para validar a eficácia do sistema.

- Analisar a precisão dos sensores, a confiabilidade da comunicação e o desempenho da interface gráfica.

- Ajustar o sistema com base nos resultados obtidos durante a validação.

## Limitações do Projeto:
- O sistema não identificará a causa específica do defeito no motor, focando apenas na detecção de comportamentos anômalos nos parâmetros monitorados (vibração e temperatura).

- A validação será realizada apenas em ambiente controlado, sem testes em campo real ou em condições industriais extremas.
