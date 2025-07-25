# **Painel Computador de Bordo para XRE300**

Este projeto visa criar um sistema de painel computador de bordo para minha atual moto **Honda XRE300**. 
O sistema fornece informações em tempo real sobre o desempenho e estado da moto, incluindo velocidade, nível de combustível, temperatura do motor, gasto de combustivel instantaneo e previsto na semana e com base em dados historicos dos mesmos periodos.
O painel também oferece funcionalidades de controle remoto, manutenção preventiva, e cálculos de gasto de combustível.

## **Funcionalidades Principais**

### **1. Monitoramento e Exibição de Dados**
- **Velocidade**: Exibição em tempo real da velocidade da moto com base na roda ou GPS
- **Nível de Combustível**: Indicador do nível de combustível com alertas para baixo nível.
- **Temperatura do Motor**: Monitoramento da temperatura do motor e alertas de superaquecimento com dados do modulo.
- **Consumo de Combustível**: Cálculo de consumo de combustível por quilômetro instantaneo.

### **2. Cálculo de Gasto de Combustível**
- **Gasto Semanal**: Cálculo do gasto de combustível semanal com gráficos e históricos diários.
- **Gasto Mensal**: Estimativa de gasto mensal e visualização do desempenho ao longo do mês.
- **Histórico de Gasto**: Relatórios detalhados de consumo em períodos anteriores.

### **3. Controle do Motor**
- **Ligar o Motor via Aplicativo Móvel**: Funcionalidade de ligar/desligar o motor remotamente.
- **Aquecimento e Lubrificação do Motor**: Programação para ligar o motor automaticamente em um horário definido para aquecer e lubrificar.


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
- **Sensores nativos da moto acessados pelaintegração com o modulo**:
  - **Sensor de Velocidade**: Para medir a velocidade da moto.
  - **Sensor de Combustível**: Para monitorar o nível de combustível.
  - **Sensor de Temperatura**: Para medir a temperatura do motor.
  - **Sensor de Pressão dos Pneus** (opcional): Para verificar a pressão dos pneus.
- **Display atualmente uso o celular como display: Exibição das informações no painel da moto.
- **Módulo Bluetooth/Wi-Fi**: Para comunicação com o aplicativo móvel e controle remoto.

---



## **Prototipagem**

### **Prototipo do Painel**
A seguir, temos uma imagem do protótipo do painel, mostrando a interface gráfica de como as informações serão exibidas na tela LCD/OLED.

<img width="1024" height="1024" alt="ChatGPT Image 24 de jul  de 2025, 20_34_40" src="https://github.com/user-attachments/assets/866eb16e-b81e-45d4-badd-a875aa2d9204" />


### **Animação de Inicialização**
A animação de inicialização foi projetada para dar uma experiência interativa e moderna, exibindo as informações iniciais do painel enquanto o sistema está sendo carregado.




https://github.com/user-attachments/assets/89d3f4c9-600c-428a-9179-f8f8e04b9448



---

## **Licença**

Este projeto é licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## **Contato**

- **Autor**: Nivaldo Santiago
- **E-mail**: nivaldo.santiago@outlook.com.br
