# GGPLOT2R
Tutorial de GGPLOT2 no R.

Começamos instalando o pacote `Tidyverse` e depois carregando ele para usar:

```
#Instalando um pacote
Install.packages("tidyverse")
```

```
#Carregando um pacote
library(tidyverse)
```

Você só precisa instalar o pacote uma vez, mas precisa recarregá-lo sempre que iniciar uma nova versão.

Usaremos o data frame mpg para começar a imprimir visualizações no R. Um data frame é uma coleção retangular de variáveis (nas colunas) e observações (nas linhas).

# Primeiros Passos

##Carros com motores maiores usam mais combustível que carros com motores menores ?

```
ggplot(data = mpg)+
  geom_point(mapping = aes(x = displ, y = hwy))
```

Saída:

![image](https://user-images.githubusercontent.com/84130785/179041839-6a4024f0-fa10-4eb6-a549-73aab8136184.png)

O gráfico mostra uma relação negativa entre o tamanho do motor(displ) e a eficiência do combustível (hwy). Carros com motores maiores usam mais combustível.









