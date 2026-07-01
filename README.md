# 🏭 Simulador Interativo: Arquitetura EtherNet/IP na Indústria

**Projeto prático de demonstração da convergência TI/TA e topologias de rede industrial.**
*Desenvolvido como projeto de portfólio para a Unidade Curricular de Conectividade de Cybersistemas para Automação (Centro WEG - Jaraguá do Sul).*

---

## 📌 Sobre o Projeto e o EtherNet/IP
Este projeto é um painel estático e interativo (HTML/CSS/JS) criado para explicar como o protocolo **EtherNet/IP** funciona no chão de fábrica e como ele integra os equipamentos de Automação (TA) aos sistemas de TI.

O **EtherNet/IP** utiliza a infraestrutura física da Ethernet tradicional, mas adiciona a "inteligência industrial" do protocolo **CIP**. Ele resolve o maior desafio da Indústria 4.0: usar o mesmo cabo para controlar uma máquina em milissegundos e para enviar relatórios gerenciais para o escritório.

---

## 🔍 O que esta simulação demonstra?

| Conceito Técnico | Aplicação na Simulação |
| :--- | :--- |
| **Mensagens Explícitas (TCP/IP)** | Dados lentos e sob demanda. Usados pela TI (SCADA, ERP) para ler diagnósticos e receitas. Representados em **azul**. |
| **Mensagens Implícitas (UDP/IP)** | Dados ultrarrápidos e cíclicos. Usados pela TA (CLP, Inversores) para controle de I/O em tempo real. Representados em **verde**. |
| **Topologia DLR (Anel)** | O anel físico (linha laranja) que interliga os controladores. Se um cabo romper, a rede inverte o fluxo em menos de 3ms. |
| **Objetos CIP e EDS** | Os dados não são números crus (como no Modbus), mas sim Objetos padronizados. Arquivos EDS funcionam como "drivers". |
| **Convergência (OSI)** | Separação visual desde os cabos industriais robustos (Nível 0) até a gestão em nuvem com conectores normais (Nível 3). |

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Função no Projeto |
| :--- | :--- |
| **HTML5** | Estruturação semântica e integração de SVGs customizados desenhados no próprio código. |
| **CSS3** | Animações baseadas em Keyframes, Layout em Grid/Flexbox e UI Glassmorphism com tema escuro. |
| **JavaScript** | Lógica de exibição dos painéis modais dinâmicos e interatividade do sistema. |
| **FontAwesome** | Ícones tipográficos para a interface visual. |

---
*Este material tem caráter educativo e foi estruturado para demonstrar de forma clara a aplicação prática do protocolo industrial EtherNet/IP.*