# **Painel Computador de Bordo para XRE300**

Este projeto visa criar um sistema de painel computador de bordo para a moto **Honda XRE300**. O sistema fornece informações em tempo real sobre o desempenho e estado da moto, incluindo velocidade, nível de combustível, temperatura do motor, entre outros. O painel também oferece funcionalidades de controle remoto, manutenção preventiva, e cálculos de gasto de combustível.

## **Funcionalidades Principais**

### **1. Monitoramento e Exibição de Dados**
- **Velocidade**: Exibição em tempo real da velocidade da moto.
- **Nível de Combustível**: Indicador do nível de combustível com alertas para baixo nível.
- **Temperatura do Motor**: Monitoramento da temperatura do motor e alertas de superaquecimento.
- **Consumo de Combustível**: Cálculo de consumo de combustível por quilômetro.

### **2. Cálculo de Gasto de Combustível**
- **Gasto Semanal**: Cálculo do gasto de combustível semanal com gráficos e históricos diários.
- **Gasto Mensal**: Estimativa de gasto mensal e visualização do desempenho ao longo do mês.
- **Histórico de Gasto**: Relatórios detalhados de consumo em períodos anteriores.

### **3. Controle do Motor**
- **Ligar o Motor via Aplicativo Móvel**: Funcionalidade de ligar/desligar o motor remotamente.
- **Aquecimento e Lubrificação do Motor**: Programação para ligar o motor automaticamente em um horário definido para aquecer e lubrificar.
- **Ligar o Motor em Horário Programado**: Programação para ligar o motor automaticamente a uma hora específica.

### **4. Manutenção e Manutenção Preventiva**
- **Alertas de Manutenção**: Notificações sobre manutenções necessárias com base em tempo de uso ou quilometragem.
- **Manutenção Preventiva**: Sugestões de manutenções periódicas para prolongar a vida útil da moto.
- **Histórico de Manutenção**: Registro completo das manutenções realizadas, com data e tipo de serviço.

### **5. Alertas e Diagnóstico**
- **Alertas de Problemas**: Notificações sobre qualquer parâmetro fora do padrão (ex: temperatura alta, nível de combustível baixo).
- **Diagnóstico Automático**: Verificação do status dos sensores e componentes da moto, com relatórios de falhas.

---

## **Funcionalidades do Aplicativo Móvel**
O aplicativo móvel complementa o sistema, oferecendo controle e monitoramento remoto da moto. As funcionalidades incluem:
- Ligar/desligar o motor remotamente.
- Agendar horário de partida para aquecimento.
- Monitorar o nível de combustível, consumo e temperatura.
- Receber alertas de falhas ou necessidade de manutenção.
- Consultar histórico de manutenções e diagnósticos.

---

## **Estrutura de Hardware**

### **1. Componentes Principais**
- **ESP32**: Placa de desenvolvimento responsável pela comunicação entre sensores, motor e painel.
- **Sensores**:
  - **Sensor de Velocidade**: Para medir a velocidade da moto.
  - **Sensor de Combustível**: Para monitorar o nível de combustível.
  - **Sensor de Temperatura**: Para medir a temperatura do motor.
  - **Sensor de Pressão dos Pneus** (opcional): Para verificar a pressão dos pneus.
- **Display LCD/OLED**: Exibição das informações no painel da moto.
- **Módulo Bluetooth/Wi-Fi**: Para comunicação com o aplicativo móvel e controle remoto.

---

## **Instalação e Configuração**

### **Requisitos**
- **Placa ESP32**.
- **Sensores**: Velocidade, combustível, temperatura e pressão dos pneus (opcional).
- **Display LCD ou OLED**.
- **Arduino IDE** instalado.
- **Bibliotecas** do ESP32 e do display no Arduino IDE.

### **Passos para Instalação**
1. **Configuração do Ambiente**:
   - Baixe e instale o **Arduino IDE**.
   - Adicione a placa **ESP32** no Arduino IDE.
   
2. **Conectar os Sensores**:
   - Conecte os sensores de velocidade, combustível e temperatura à placa ESP32.
   - Conecte o display LCD ou OLED para exibição das informações.

3. **Carregar o Código**:
   - Abra o código fonte no Arduino IDE.
   - Selecione a placa **ESP32** e carregue o código para o dispositivo.

4. **Configuração do Aplicativo Móvel**:
   - Desenvolva o aplicativo móvel para controle via Bluetooth ou Wi-Fi.
   - O aplicativo pode ser desenvolvido em **Flutter**, **React Native**, ou outras tecnologias de sua preferência.

---

## **Prototipagem**

### **Prototipo do Painel**
A seguir, temos uma imagem do protótipo do painel, mostrando a interface gráfica de como as informações serão exibidas na tela LCD/OLED.

<img width="1024" height="1024" alt="ChatGPT Image 24 de jul  de 2025, 20_34_40" src="https://github.com/user-attachments/assets/866eb16e-b81e-45d4-badd-a875aa2d9204" />


### **Animação de Inicialização**
A animação de inicialização foi projetada para dar uma experiência interativa e moderna, exibindo as informações iniciais do painel enquanto o sistema está sendo carregado.



---

## **Contribuindo para o Projeto**

Se você deseja contribuir para o projeto, siga os seguintes passos:

1. **Faça um fork** deste repositório para sua conta.
2. **Crie uma branch** com suas melhorias ou correções.
3. **Submeta um pull request** explicando as alterações feitas.

---

## **Licença**

Este projeto é licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## **Contato**

- **Autor**: Nivaldo Santiago
- **E-mail**: nivaldo.santiago@exemplo.com
