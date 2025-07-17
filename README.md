# Exemplos de Layout com CSS Grid

Este repositório contém três exemplos distintos de layout utilizando **CSS Grid**, desenvolvidos como parte dos meus estudos práticos na disciplina de Desenvolvimento Web da FATEC Mococa.

Cada exemplo tem uma estrutura semelhante, mas utiliza diferentes formas de manipular o posicionamento dos elementos com `grid`.

---

## 📁 grid1.html

Neste exemplo, a disposição dos elementos é feita com o uso de **linhas e colunas explícitas**, utilizando `grid-column` e `grid-row`. A grid é composta por 3 colunas e 4 linhas. O layout possui:

- `header` ocupando a linha inteira no topo  
- `nav` e `main` lado a lado  
- `aside` posicionado à direita  
- `footer` na base, ocupando toda a largura

---

## 📁 grid2.html

Aqui, o layout também é feito com linhas e colunas, mas com variações:

- O `nav` é posicionado no canto superior direito, com `margin`  
- O `aside` está ajustado entre a 2ª e 3ª coluna  
- O `main` ocupa duas colunas e duas linhas  
- A organização visual muda um pouco em relação ao exemplo anterior, explorando mais liberdade nos blocos

---

## 📁 grid3.html

Neste caso, a grid é configurada usando **áreas nomeadas** com `grid-template-areas`. Essa abordagem facilita a visualização e o entendimento do layout, deixando o código mais legível. A estrutura definida é:

