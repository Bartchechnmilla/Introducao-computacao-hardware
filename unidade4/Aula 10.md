# Aula 10 – Redes de Computadores: Histórico, Elementos e Classificação

## Nome(s) dos estudante(s): Felipe Bartchechn Milla e matrícula(s): 22611099

## Objetivo
Compreender a evolução das redes de computadores, identificar seus elementos básicos e classificar diferentes tipos de redes.

### 1. Linha do Tempo

# ⏳ Evolução das Redes de Computadores

## Marcos Históricos

| Período | Marco | Descrição | Tecnologia Chave |
| :--- | :--- | :--- | :--- |
| **1950 - 1960** | 🖥️ **Mainframes** | Sistemas de processamento centralizado onde terminais remotos se conectavam a um único computador de grande porte. | Terminais "Burros" |
| **1969** | 🌐 **ARPANET** | Primeira rede baseada em comutação de pacotes, criada para garantir comunicação descentralizada e resiliente. | Comutação de Pacotes |
| **1983** | 📑 **TCP/IP** | Adoção oficial dos protocolos TCP/IP, permitindo que diferentes redes "falassem" a mesma língua. O nascimento da Internet. | Pilha de Protocolos |
| **1990s** | 🌍 **Internet Comercial** | Criação da World Wide Web (WWW) e abertura da rede para o público e empresas através de navegadores. | HTTP e HTML |
| **2000 - Hoje** | 📱 **Redes Móveis** | Evolução da banda larga móvel (3G, 4G, 5G), tornando a conexão onipresente em smartphones e dispositivos IoT. | LTE / 5G / Wi-Fi |

---

### 2. Elementos da Rede

![Diagrama ilustrado](elementos.png)

### 📋 Tabela: Elementos Fundamentais da Comunicação

| Elemento | Função Principal | Exemplos Reais | Meio/Formato |
| :--- | :--- | :--- | :--- |
| **Emissor** | Origina e codifica a mensagem para envio. | Smartphone, Laptop, Câmera de Segurança. | Digital ou Analógico |
| **Receptor** | Recebe e decodifica a mensagem para o destino. | Servidor Cloud, Smart TV, Tablet. | Processamento de Sinal |
| **Meio** | Caminho físico ou sem fio por onde os dados trafegam. | Fibra Óptica, Cabo de Rede (UTP), Ondas de Rádio. | Físico (Guiado/Não guiado) |
| **Protocolo** | Regras que garantem que todos "falem a mesma língua". | TCP/IP, HTTP, Bluetooth, MQTT. | Lógico (Software/Normas) |

### 3. Classificação de Redes
# 🗺️ Classificação e Abrangência de Redes

A classificação das redes baseia-se na distância geográfica que a infraestrutura cobre, desde o uso pessoal até ao nível global.

---

## 📊 Quadro Comparativo: Tipos de Redes

| Sigla | Nome Completo | Abrangência Geográfica | Exemplo Real |
| :--- | :--- | :--- | :--- |
| **PAN** | *Personal Area Network* | **Pessoal** (até 10m) | Ligação **Bluetooth** entre telemóvel e fone de ouvido. |
| **LAN** | *Local Area Network* | **Local** (Edifício/Sala) | Rede Wi-Fi **doméstica** ou computadores de um **laboratório**. |
| **MAN** | *Metropolitan Area Network* | **Metropolitana** (Cidade) | Rede que liga vários polos de uma **Universidade** ou **Prefeitura**. |
| **WAN** | *Wide Area Network* | **Mundial** (Países) | A própria **Internet** conectando continentes. |

---

## 📍 Mapa Conceitual

Este mapa ilustra a hierarquia das redes (da menor para a maior). Se o teu editor de Markdown suportar **Mermaid**, verás um diagrama visual abaixo:

```mermaid
graph TD
    A[Redes de Computadores] --> B{Abrangência}
    
    B --> PAN[PAN: Pessoal]
    B --> LAN[LAN: Local]
    B --> MAN[MAN: Metropolitana]
    B --> WAN[WAN: Mundial]
    
    PAN --- P1[Ex: Bluetooth Celular + Fone]
    LAN --- L1[Ex: Rede de Laboratório / Wi-Fi Casa]
    MAN --- M1[Ex: Rede Campus Universitário / Prefeitura]
    WAN --- W1[Ex: Internet / Cabos Submarinos]

    style PAN fill:#f9f,stroke:#333
    style LAN fill:#bbf,stroke:#333
    style MAN fill:#dfd,stroke:#333
    style WAN fill:#fdb,stroke:#333
```

## Organização dos Arquivos
- Criar uma pasta com o nome do grupo (ex.: `Grupo1_Windows`, `Grupo2_Linux`).
- Dentro da pasta, incluir:
  - `linha_tempo.pdf` ou `linha_tempo.png`
  - `elementos_rede.png` ou `elementos_rede.pdf`
  - `classificacao_redes.pdf` ou `classificacao_redes.png`
  - `README.md` com breve descrição do trabalho.

Livro ![Livro de Rede de computadores do Tanenbaum]([https://archive.org/details/tanenbaum-rede-de-computadores-6a/mode/2up](https://ia601603.us.archive.org/BookReader/BookReaderImages.php?zip=/19/items/tanenbaum-rede-de-computadores-6a/Tanenbaum%20Rede%20de%20Computadores%206a_jp2.zip&file=Tanenbaum%20Rede%20de%20Computadores%206a_jp2/Tanenbaum%20Rede%20de%20Computadores%206a_0000.jp2&id=tanenbaum-rede-de-computadores-6a&scale=2&rotate=0))
---
