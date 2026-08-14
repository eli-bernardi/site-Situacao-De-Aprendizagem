# Del Company – Portfólio de Serviços e Plataforma Educativa de Tecnologia

[![GitHub last commit](https://img.shields.io/github/last-commit/eli-bernardi/Del-Company)](https://github.com/eli-bernardi/Del-Company/commits/main)
[![GitHub repo size](https://img.shields.io/github/repo-size/eli-bernardi/Del-Company)](https://github.com/eli-bernardi/Del-Company)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Plataforma web institucional e educativa desenvolvida para apresentar serviços de tecnologia, portfólio de projetos, fundamentos de programação, automação, sensoriamento IoT e robótica industrial.

**Link de acesso online:** [del-company.vercel.app](https://del-company.vercel.app)

---

## Conteúdo

- [Visão Geral](#visão-geral)
- [Funcionalidades e Destaques](#funcionalidades-e-destaques)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Páginas e Seções](#páginas-e-seções)
  - [Institucional](#1-institucional)
  - [Serviços e Fundamentos](#2-serviços-e-fundamentos)
  - [Robótica Industrial](#3-robótica-industrial)
  - [Sensoriamento & IoT](#4-sensoriamento--iot)
- [Como Executar Localmente](#como-executar-localmente)
- [Licença](#licença)
- [Contato](#contato)

---

## Visão Geral

O **Del Company** combina uma vitrine institucional de serviços em tecnologia com um portal de conteúdo técnico. A aplicação apresenta tópicos fundamentais da computação e da engenharia moderna:

- **Lógica de Programação & Algoritmos**: Linguagens compiladas vs. interpretadas e programas funcionais em JavaScript.
- **Banco de Dados**: Modelagem DER/MER, SGBDs relacionais/NoSQL e sintaxe SQL.
- **Sistemas de Rede**: Topologias de rede, equipamentos, modelo OSI e pilha TCP/IP.
- **Fundamentos de Eletrônica**: Componentes, cálculo de circuitos em tempo real (Lei de Ohm/Potência), cronologia e microcontroladores.
- **Tecnologia da Informação**: Hardware, sistemas operacionais e softwares de escritório.
- **Robótica Industrial**: Catálogo completo de 7 arquiteturas cinemáticas industriais (Articulado, Cartesiano, Cilíndrico, Colaborativo, Delta, Polar e SCARA) com especificações técnicas e modelos comerciais reais.
- **Sensoriamento & IoT**: Visão geral de sensoriamento, catálogo visual de sensores, protocolos de comunicação (I²C, SPI, UART, 4–20 mA, IO-Link) e integração com ecossistemas IoT/IIoT.

O design adota um tema dark minimalista com detalhes em vermelho (#d62828), animações com Intersection Observer, cards responsivos e navegação uniforme.

---

## Funcionalidades e Destaques

- **Navegação Uniforme:** Header fixo com menu dropdown responsivo para Serviços, Robótica e Sensores em todas as páginas.
- **Módulos Interativos em JavaScript:**
  - Ordenadores de vetores (Bubble Sort) visualizáveis em tempo real.
  - Calculadora de IMC, conversor de temperatura e algoritmos de busca.
  - Calculador de circuitos elétricos (Lei de Ohm e Potência).
- **Catálogo de Robótica Industrial:** Detalhes de graus de liberdade, alcance, carga útil, repetibilidade e fabricantes reais (FANUC, KUKA, ABB, UR, Yaskawa, Epson, Stäubli).
- **Seção de Sensoriamento IoT:** Apresentação visual de sensores (LM35, DHT11/22, DS18B20, HC-SR04, LDR, PIR, MQ-2/135, BMP280, MPU6050, ACS712, indutivos, capacitivos, fotoelétricos etc.) em cards responsivos e sem cortes.
- **Visualização de Protocolos Industriais:** Diagramas explicativos de barramentos digitais e analógicos (I²C, SPI, UART, 4–20 mA e IO-Link).
- **Design Responsivo:** Adaptado para dispositivos móveis, tablets e telas de alta resolução.

---

## Tecnologias Utilizadas

| Tecnologia | Finalidade no Projeto |
| :--- | :--- |
| **HTML5** | Estrutura semântica das páginas e formulários |
| **CSS3** | Estilização personalizada, animações CSS, flexbox/grid e layout responsivo |
| **JavaScript (ES6+)** | Lógica interativa, cálculos, controles de menu, carrossel e animações de scroll |
| **Tailwind CSS** | Utilitários de suporte de cores e layout (via CDN) |
| **Google Fonts (Inter)** | Tipografia moderna e legível |
| **Vercel** | Plataforma de hospedagem e deploy contínuo |
| **Git & GitHub** | Controle de versão e portfólio de código |

---

## Estrutura do Projeto

```text
Del-Company/
├── index.html                 # Página Inicial (Home)
├── service.html               # Catálogo de Serviços e Projetos
├── contato.html               # Formulário e Canais de Contato
├── img/                       # Logos, avatares e favicon (dell.png)
├── README.md                  # Documentação do projeto
└── service/
    ├── robots/
    │   ├── css/               # Estilos das páginas de robôs
    │   ├── html/              # Páginas dos 7 modelos de robôs industriais
    │   ├── img/               # Fotos e ilustrações de robôs
    │   └── js/                # Scripts auxiliares para robótica
    ├── sensors/
    │   ├── css/               # Folha de estilo unificada (sensores.css)
    │   ├── html/              # Seções de sensoriamento, tipos, comunicação e IoT
    │   ├── img/               # Diagramas didáticos e fotos de sensores
    │   └── js/                # Scripts de animação e interatividade
    └── servicos/
        ├── css/               # Estilos por matéria/conteúdo técnico
        ├── html/              # Páginas educativas (robotizacao, sensores, banco_dados, etc.)
        ├── img/               # Diagramas de arquitetura, apostilas e ilustrações
        └── js/                # Lógica dos programas interativos
```

---

## Páginas e Seções

### 1. Institucional
- **Home (`index.html`)**: Apresentação da empresa, equipe, serviços principais e localização.
- **Serviços (`service.html`)**: Portfólio de serviços, catálogo de projetos e carrossel interativo.
- **Contato (`contato.html`)**: Formulário de mensagem e links diretos para canais de atendimento.

### 2. Serviços e Fundamentos
- **Lógica de Programação (`logica_programacao.html`)**: Conceitos de algoritmos, linguagens e executáveis práticos.
- **Banco de Dados (`banco_dados.html`)**: SGBDs, diagramas DER/MER, consultas SQL e exemplos.
- **Sistemas de Rede (`fundamentos_rede.html`)**: Equipamentos de rede, modelo OSI, pilha TCP/IP e exemplos em Node.js.
- **Lógica Computacional (`logica_computacional.html`)**: Fluxogramas, tabelas verdade, algoritmos e Portugol.
- **Fundamentos de Eletrônica (`fundamentos_eletronica.html`)**: Componentes eletrônicos, cronologia, simulação de circuitos e Arduino.
- **Tecnologia da Informação (`tecnologia_informacao.html`)**: Arquitetura de computadores, sistemas operacionais e suítes de escritório.

### 3. Robótica Industrial
- **Visão Geral (`robotizacao.html`)**: Introdução à automação robótica e Indústria 4.0.
- **Robô Cartesiano (`robo_cartesiano.html`)**: Coordenadas retangulares XYZ e pontes rolantes.
- **Robô SCARA (`robo_scara.html`)**: Movimentos em plano horizontal para pick-and-place de alta velocidade.
- **Robô Articulado (`robo_articulado.html`)**: Manipuladores de 6 eixos com máxima flexibilidade.
- **Robô Cilíndrico (`robo_cilindrico.html`)**: Geometria de trabalho cilíndrica.
- **Robô Delta (`robo_delta.html`)**: Robôs paralelos para separação ultrarrápida.
- **Robô Polar (`robo_polar.html`)**: Coordenadas esféricas r, θ, φ.
- **Robô Colaborativo (`robo_colaborativo.html`)**: Cobots operando com segurança ao lado de humanos.

### 4. Sensoriamento & IoT
- **Visão Geral (`sensores.html`)**: Conceito de sensoriamento, transdutores e aplicações por setor.
- **Introdução aos Sensores (`sensor-introduca.html`)**: Princípios físicos, variáveis de processo e características técnicas (precisão, resolução, sensibilidade).
- **Tipos de Sensores (`sensor-tipos.html`)**: Catálogo visual detalhado de sensores de temperatura, umidade, distância, luz, movimento, gás, aceleração, corrente e sensores industriais.
- **Comunicação com Sensores (`sensor-comunicacao.html`)**: Funcionamento dos barramentos I²C, SPI, UART, laço de corrente 4–20 mA e IO-Link.
- **Plataformas & IoT (`sensor-plataformas.html`)**: Integração de sensores com Arduino, ESP32, Raspberry Pi, CLP industrial e arquitetura para a nuvem.

---

## Como Executar Localmente

1. Clone este repositório:
   ```bash
   git clone https://github.com/eli-bernardi/Del-Company.git
   ```

2. Acesse o diretório do projeto:
   ```bash
   cd Del-Company
   ```

3. Abra o arquivo `index.html` em qualquer navegador moderno (ou utilize a extensão **Live Server** no VS Code).

> O projeto é 100% estático (HTML/CSS/JS), sem necessidade de instalação de dependências ou gerenciadores de pacote.

---

## Licença

Este projeto está sob a licença **MIT**. Para mais detalhes, consulte o arquivo LICENSE.

---

## Contato

**Eliel Bernardi**  
- **Instagram:** [instagram.com/elielbrnrd](https://www.instagram.com/elielbrnrd/)
- **WhatsApp:** [wa.me/5548991013184](https://wa.me/5548991013184)
- **GitHub:** [github.com/eli-bernardi](https://github.com/eli-bernardi)
- **E-mail:** elielbernardi0012@gmail.com
