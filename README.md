# 🕹️ Detona Ralph - Jogo Whac-A-Mole (Desafio DIO + Melhorias)

Este projeto é baseado no desafio proposto pela [Digital Innovation One (DIO)](https://www.dio.me/), no qual foi desenvolvido um mini jogo inspirado no clássico "Whac-A-Mole", com visual e tema do personagem **Ralph** do filme *Detona Ralph*.

## 🎯 Objetivo do Jogo

- Clique rapidamente no quadrado onde o inimigo aparece.
- Aumente sua pontuação a cada acerto.
- O jogo tem tempo limitado e o inimigo aparece em posições aleatórias.



## 📌 Desafio Original (DIO)

O projeto original fornecido pela DIO incluía:

- Interface básica com grade de quadrados.
- Exibição de inimigo em posições aleatórias.
- Contador de tempo regressivo.
- Contador de pontuação com som ao acertar o inimigo.



## ✅ Melhorias Implementadas 

1. **❤️ Sistema de Vidas**
   - O jogador inicia com **3 vidas** (`x3` visível na interface).
   - A cada clique incorreto (fora do inimigo), **perde uma vida**.

2. **💀 Game Over Personalizado**
   - Quando as vidas chegam a `0`, o jogo exibe um alerta:  
     **"Game Over. Tente novamente!"**
   - A página é **recarregada automaticamente** após a derrota.

3. **🔁 Atualização Visual das Vidas**
   - O número de vidas visível no HTML é atualizado dinamicamente (`x3`, `x2`, `x1`...).

4. **🧼 Código Refatorado**
   - Comentários explicativos foram adicionados ao JavaScript (`engine.js`).
   - Lógica modularizada com melhor legibilidade e separação clara de responsabilidades.


## 🧪 Tecnologias Utilizadas
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)



## 📚 Créditos

Projeto original fornecido pela [Digital Innovation One (DIO)](https://dio.me).

Melhorias de lógica e interatividade desenvolvidas por Cristiane Machado.
