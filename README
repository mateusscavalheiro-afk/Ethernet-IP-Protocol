# 🏭 Simulador Interativo: Arquitetura EtherNet/IP na Indústria

**Projeto prático de demonstração da convergência TI/TA e topologias de rede industrial.**
*Desenvolvido como projeto de portfólio para a Unidade Curricular de Conectividade de Cybersistemas para Automação (Centro WEG - Jaraguá do Sul).*

---

## 📌 Sobre o Projeto
Este projeto é um painel estático e interativo em HTML/CSS/JS (Dashboard) criado para explicar, de forma visual e didática, como o protocolo **EtherNet/IP** funciona no chão de fábrica e como ele integra os equipamentos de Tecnologia da Automação (TA) aos sistemas de Tecnologia da Informação (TI).

O objetivo é substituir diagramas estáticos por uma simulação animada onde o usuário pode interagir com os equipamentos (CLPs, Inversores, Robôs, Servidores) e visualizar o fluxo de dados e os conceitos físicos/lógicos aplicados em tempo real.

---

## 🌐 O que é o EtherNet/IP?
O **EtherNet/IP** (Industrial Protocol) não é apenas a internet comum ligada em uma máquina. Trata-se de um protocolo de rede industrial padrão e aberto, gerenciado pela ODVA, que utiliza a infraestrutura física da Ethernet tradicional (cabos de rede, switches TCP/IP), mas adiciona uma camada de "inteligência industrial" chamada **CIP (Common Industrial Protocol)**.

Ele resolve o maior desafio da Indústria 4.0: usar o mesmo cabo para controlar uma máquina em milissegundos e para enviar relatórios gerenciais para o escritório.

---

## 🔍 O que esta simulação demonstra?

O dashboard interativo aborda os seguintes pilares do EtherNet/IP:

1. **Mensagens Explícitas vs. Implícitas (O Tráfego de Dados):**
   - 🟦 **TCP/IP (Explícito):** Dados lentos, não críticos e sob demanda, usados pela TI (SCADA, ERP) para ler diagnósticos e receitas de produção.
   - 🟩 **UDP/IP (Implícito):** Dados ultrarrápidos e cíclicos, usados pela TA (CLP, Robôs, Inversores) para controle de I/O em tempo real.

2. **Topologia DLR (Device Level Ring):**
   - A animação demonstra (em laranja) o anel físico que interliga os controladores. O DLR permite que, se um cabo romper no chão de fábrica, a rede inverta o sentido dos pacotes em menos de 3 milissegundos, evitando a parada da linha de produção.

3. **Modelo de Objetos CIP & Arquivos EDS:**
   - Na seção de "Simulações Avançadas", o projeto demonstra visualmente como os dados não são meros números (como no Modbus clássico), mas sim *Objetos CIP* padronizados. Também ilustra como os *Arquivos EDS* funcionam como "drivers" para configurar os equipamentos facilmente no CLP Mestre.

4. **Convergência de Camadas (Modelo OSI e Purdue):**
   - O projeto divide o mapa físico em camadas, mostrando quais cabos industriais (como os conectores robustos M12) são usados no chão de fábrica (Nível 0) e como a informação sobe até a gestão (Nível 3) usando conectores RJ45 normais.

---

## 🛠️ Tecnologias Utilizadas
* **HTML5:** Estruturação semântica e integração de SVGs customizados desenhados no próprio código.
* **CSS3:** Animações baseadas em Keyframes, Layout em Grid/Flexbox e UI Glassmorphism com tema escuro.
* **Vanilla JavaScript:** Lógica de exibição dos painéis modais dinâmicos e interatividade do sistema.
* **FontAwesome:** Ícones tipográficos para a interface.

---
*Este material tem caráter educativo e foi estruturado para demonstrar de forma clara a aplicação prática do protocolo industrial EtherNet/IP.*
