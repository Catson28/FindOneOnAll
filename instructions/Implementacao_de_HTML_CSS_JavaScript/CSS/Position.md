[![Instruções](https://img.shields.io/badge/Back-red?style=for-the-badge)](readme.md)

![](img/1_x5xm9DVS6QouWCAeII9w8A.png)

![](img/css-position-all.png)

![](img/CSS-position.webp)

![](img/css-positioning-schemes-790d5b.3d581d20.png)

## Position
1. **Static (Padrão)**:
   ```css
   .element {
       position: static;
   }
   ```
2. **Relative (Posição Relativa ao Pai)**:
   ```css
   .element {
       position: relative;
       top: 20px;
       left: 30px;
   }
   ```
3. **Absolute (Posição Absoluta)**:
   ```css
   .element {
       position: absolute;
       top: 50%;
       left: 50%;
       transform: translate(-50%, -50%);
   }
   ```
4. **Fixed (Posição Fixa na Tela)**:
   ```css
   .element {
       position: fixed;
       top: 0;
       right: 0;
   }
   ```