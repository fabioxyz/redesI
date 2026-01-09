# 🌐 Simulação de Rede - Cisco Packet Tracer

Este repositório contém um projeto de infraestrutura de redes desenvolvido no **Cisco Packet Tracer**. O projeto foca-se na implementação, configuração e conectividade de dispositivos de rede (Routers, Switches e End-devices).

## 🚀 Objetivo do Projeto
O objetivo principal desta atividade foi realizar a configuração lógica e física de uma rede, garantindo a comunicação eficiente entre diferentes sub-redes e aplicando boas práticas de administração de redes Cisco.

## 🛠️ Tecnologias e Conceitos Implementados
* **Software:** Cisco Packet Tracer.
* **Addressing:** Planeamento de endereçamento IP (IPv4).
* **Routing & Switching:** Configuração de interfaces, tabelas de encaminhamento e conectividade básica.
* **CLI:** Configuração via linha de comandos (Cisco IOS).
* **Etherchannel:** Configuraçao de Port-Channels e Trunks.

## 📂 Estrutura do Repositório
* `AL4_PT_1(3).pka`: Ficheiro de simulação pronto a ser executado no Packet Tracer.
* `README.md`: Documentação do projeto.

## 📸 Topologia
> **Nota:** Adiciona aqui um screenshot da tua rede para que quem visita o perfil consiga ver o teu trabalho sem ter de baixar o ficheiro!
> 
> ![Topologia da Rede]([link-da-tua-imagem-aqui.png](https://imgur.com/a/7A8REGE))

## ⚙️ Como Executar
1. Certifica-te de que tens o **Cisco Packet Tracer** instalado.
2. Faz o download do ficheiro `AL4_PT_1(3).pka`.
3. Abre o ficheiro com o simulador.
4. Explora as configurações através do terminal (CLI) dos dispositivos.

## 📄 Exemplo de Configuração (CLI)
Um exemplo básico das configurações aplicadas nos dispositivos:
```bash
Router> enable
Router# configure terminal
Router(config)# interface GigabitEthernet0/0
Router(config-if)# ip address 192.168.1.1 255.255.255.0
Router(config-if)# no shutdown
