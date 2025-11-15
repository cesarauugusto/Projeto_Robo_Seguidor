#!/usr/bin/env bash

cat > README.md << 'EOF'
# Robô Seguidor de Linha – Projeto em Proteus 8.12

<!-- Badges do Projeto -->
![Status](https://img.shields.io/badge/Status-Ativo-brightgreen)
![Projeto](https://img.shields.io/badge/Projeto-Seguidor%20de%20Linha-blue)
![Plataforma-Proteus_8.12](https://img.shields.io/badge/Plataforma-Proteus_8.12-purple)
![Arduino](https://img.shields.io/badge/Arduino-Nano-orange)

<!-- Badges Técnicas -->
![Sensores](https://img.shields.io/badge/Sensores-QTR_Genérico-informational)
![Driver](https://img.shields.io/badge/Driver-TB6612FNG-yellow)
![Motores](https://img.shields.io/badge/Motores-6V-red)
![Bateria](https://img.shields.io/badge/Bateria-LiPo_7.4V-lightgrey)

<!-- Badges de Simulação -->
![Simulação](https://img.shields.io/badge/Simulação-Proteus_8.12-blueviolet)

<!-- Badges de Código -->
![Linguagem](https://img.shields.io/badge/Linguagem-C/C++-blue)
![Firmware](https://img.shields.io/badge/Firmware-ArduinoIDE-success)
![Código](https://img.shields.io/badge/Repositório-QTR_Sensor_Genérico-green)

<!-- Badges de Documentação -->
![Artigo](https://img.shields.io/badge/Artigo-SENGI_2020-important)
![Publicação](https://img.shields.io/badge/Publicação-E--Book-orange)

<!-- Badges de Contribuição -->
![Contribuições](https://img.shields.io/badge/Contribuições-Bem_vindas-brightgreen)
![Licença](https://img.shields.io/badge/Licença-Livre-blue)


---

Este repositório apresenta um **projeto completo de um robô seguidor de linha básico**, eficiente e de baixo custo, ideal para estudantes, iniciantes em robótica móvel e entusiastas que desejam entender os fundamentos desse tipo de sistema.

O projeto foi inteiramente desenvolvido e simulado no **Proteus 8.12**, incluindo sensores, controle, drivers e motorização.

---

## ⚙️ Download do Proteus 8.12

Para simular o projeto, é necessário o Proteus 8.12.  
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

O robô utiliza sensores QTR para identificar a faixa e controla a velocidade dos motores usando a ponte H **TB6612FNG** e um **Arduino Nano**.

---

## 🧩 Componentes Utilizados

- Sensor QTR genérico  
- Ponte H **TB6612FNG**  
- **Arduino Nano**  
- Dois motores DC 6 V  
- Bateria LiPo 7,4 V  
- Cabos, conectores e elementos passivos

> Este projeto foi pensado para iniciantes: simples, acessível e eficiente.

---

## 📸 Imagens dos Componentes (Adicionar Depois)

### 🔌 Sensor QTR  
*(espaço para imagem)*  

---

### ⚙️ Motores  
*(espaço para imagem)*  

> O motor utilizado foi o **Micro Metal GearMotor MP 6V**, 3000 RPM, caixa 10:1 e corrente de 0,67 A.  
> *(Trecho do artigo citado pelo autor)*

---

### 🔧 Ponte H TB6612FNG  
*(espaço para imagem)*  

> Suporta até 13V, fornece até 3A de pico por canal.  
> *(Trecho citado do artigo)*

---

### 🔋 Bateria LiPo  
*(espaço para imagem)*  

> Modelo usado: **LiPo 7,4V – 500 mAh**.  
> *(Trecho citado do artigo)*

---

### 🧠 Arduino Nano  
*(espaço para imagem)*  

> Usado por ser leve, compacto e programável direto via USB.  
> *(Trecho citado do artigo)*

---

## ⚡ Velocidade Recomendadas dos Motores

Entre **1000 e 2000 RPM** para iniciantes.  
Motores mais rápidos exigem controle mais sofisticado.

---

## 📄 Artigos e Referências

📘 SENGI 2020:  
https://www.even3.com.br/anais/sengi2020/271818/

📗 Publicação na revista (E-book):  
https://web.archive.org/web/20201209112322id_/https://www.uniedusul.com.br/wp-content/uploads/2020/10/E-BOOK-GESTAO-EMPRESARIAL-TEORIA-E-PRATICA.pdf#page=28

---

## 💻 Código do Robô

Código-fonte completo:  
https://github.com/cesarauugusto/QTR_Sensor_Generico

---

## 🛠️ Simulação no Proteus

O projeto inclui:

- Arduino Nano  
- Leitura dos sensores QTR  
- Ponte H TB6612FNG  
- Motores 6V  
- Pista para simulação  

---

## 📂 Estrutura do Repositório

