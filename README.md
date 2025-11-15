# Robô Seguidor de Linha – Projeto em Proteus 8.12

<!-- Badges do Projeto -->
![Status](https://img.shields.io/badge/Status-Ativo-brightgreen)
![Projeto](https://img.shields.io/badge/Tipo-Seguidor%20de%20Linha-blue)
![Plataforma](https://img.shields.io/badge/Plataforma-Proteus%208.12-purple)
![Arduino](https://img.shields.io/badge/Microcontrolador-Arduino%20Nano-orange)

<!-- Badges Técnicas -->
![Sensores](https://img.shields.io/badge/Sensor-QTR%20Genérico-informational)
![Driver](https://img.shields.io/badge/Ponte%20H-TB6612FNG-yellow)
![Motores](https://img.shields.io/badge/Motores-6V-red)
![Bateria](https://img.shields.io/badge/Bateria-LiPo%207.4V-lightgrey)

<!-- Badges de Documentação -->
![Artigo](https://img.shields.io/badge/Artigo-SENGI%202020-important)
![Publicação](https://img.shields.io/badge/Publicação-E--book-orange)

<!-- Badges de Contribuição -->
![Contribuições](https://img.shields.io/badge/Contribuições-Bem%20vindas-brightgreen)
![Licença](https://img.shields.io/badge/Licença-Livre-blue)

---

Este repositório apresenta um **projeto completo de um robô seguidor de linha básico**, eficiente e de baixo custo, ideal para estudantes, iniciantes em robótica móvel e entusiastas que desejam entender os fundamentos desse tipo de sistema.

O projeto foi inteiramente desenvolvido e simulado no **Proteus 8.12**, incluindo sensores, controle, drivers e motorização.

---

## 👤 Autor

Este projeto foi desenvolvido por **César Caugus Victor**,  
aluno da **Pós-Graduação de Mestrado em Engenharia Elétrica e de Computação pela Universidade Federal do Ceará (UFC)**.

O objetivo deste projeto é fornecer uma base educacional simples, acessível e eficiente para ajudar iniciantes em robótica móvel e eletrônica embarcada.

---

## 📦 Sobre este Repositório

Este repositório contém **apenas os arquivos dos componentes, esquemáticos, layout e placa do Proteus**, permitindo que qualquer pessoa possa:

- Visualizar o circuito completo  
- Editar e simular no Proteus 8.12  
- Fabricar sua própria PCB  
- Estudar o hardware utilizado no robô  

⚠ **IMPORTANTE:**  
O repositório **NÃO** contém o código-fonte do robô.  
O firmware está disponível separadamente em:

👉 **Repositório do Código (QTR Genérico):**  
https://github.com/cesarauugusto/QTR_Sensor_Generico

---

## ⚙️ Download do Proteus 8.12

Para executar a simulação, utilize o Proteus 8.12.  
Você pode baixar e instalar através do link abaixo:

👉 **Download Proteus 8.12:**  
https://drive.google.com/drive/folders/16IOtGxkFPdnRsD6lFqEz00AhovXTidr-?usp=drive_link

---

## 🚗 Sobre o Robô

Este seguidor de linha foi desenvolvido com foco em:

- **Baixo custo**
- **Facilidade de montagem**
- **Componentes acessíveis**
- **Boa performance para iniciantes**
- **Simulação completa no Proteus**

O robô utiliza sensores QTR para detectar a linha e controla dois motores DC através da ponte H **TB6612FNG**, comandados por um **Arduino Nano**.

---

## 🧩 Componentes Utilizados

- **Sensor de refletância QTR genérico**
- **Ponte H TB6612FNG**
- **Arduino Nano (ATmega328P)**
- **2 Motores DC 6V**
- **Bateria LiPo 7,4 V**
- Componentes passivos (capacitores, resistores, conectores, etc.)

> Este projeto foi pensado para iniciantes: simples, acessível e eficiente.

---

## 📸 Imagens dos Componentes (Adicionar Depois)

### 🔌 Sensor QTR  
*(espaço reservado para imagem)*  

---

### ⚙️ Motores  
*(espaço reservado para imagem)*  

> O motor utilizado foi o **Micro Metal GearMotor MP 6V**, com velocidade de **3000 RPM**, caixa de redução **10:1** e corrente de **0,67 A**.  
> Para iniciantes, recomenda-se motores entre **1000 e 2000 RPM**, o que facilita o controle.

---

### 🔧 Ponte H – TB6612FNG  
*(espaço reservado para imagem)*  

> O driver **TB6612FNG** possui dois canais, suporta até **13V**, e fornece picos de até **3A por canal**, sendo ideal para pequenos robôs seguidores de linha.

---

### 🔋 Bateria LiPo  
*(espaço reservado para imagem)*  

> Utilizada uma bateria **LiPo Zippy 7,4V – 500 mAh**, modelo ideal por sua leveza e alta capacidade de descarga.

---

### 🧠 Arduino Nano  
*(espaço reservado para imagem)*  

> O **Arduino Nano** foi escolhido por ser compacto, leve e programável via USB.  
> Os pinos analógicos A0–A7 foram utilizados para leitura dos sensores.

---

## ⚡ Velocidade Recomendada dos Motores

Para robôs educacionais e de iniciantes:

- Ideal: **1000–2000 RPM**
- Motores acima de 3000 RPM requerem controle mais avançado
- Motores mais lentos são mais estáveis

---

## 📄 Artigos e Referências

📘 **Artigo nos Anais da SENGI 2020:**  
https://www.even3.com.br/anais/sengi2020/271818/

📗 **Publicação no E-book "Gestão Empresarial – Teoria e Prática":**  
https://web.archive.org/web/20201209112322id_/https://www.uniedusul.com.br/wp-content/uploads/2020/10/E-BOOK-GESTAO-EMPRESARIAL-TEORIA-E-PRATICA.pdf#page=28

> Alguns trechos deste README foram extraídos e adaptados do artigo do autor.

---

## 💻 Código do Robô

👉 **Repositório do Código (QTR Genérico):**  
https://github.com/cesarauugusto/QTR_Sensor_Generico

---

## 🛠️ Simulação no Proteus

Os arquivos incluem:

- Arduino Nano  
- Sensores QTR genéricos  
- Ponte H TB6612FNG  
- Motores 6V  
- Pista para simulação  
- Esquemático  
- Layout da placa (PCB)

---

## 📂 Estrutura do Repositório

```text
📦 Seguidor-de-Linha-Proteus
 ┣ 📁 Proteus_Project
 ┣ 📁 Imagens
 ┣ 📁 Documentos
 ┣ 📄 README.md
 ┗ 📄 Licença
