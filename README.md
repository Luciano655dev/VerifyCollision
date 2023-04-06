# Verify Collision
Uma aplicação que verifica se dois círculos estão colidindo utilizando o Teorema de Pitágoras

# Como funciona
### Primeiramente, precisamos entender *como um círculo funciona*
![image](https://user-images.githubusercontent.com/83819836/230248065-5d58aeb3-06d3-4295-840b-9dabe50b1844.png)
#### EM um círculo, obtemos o raio dividindo seu diametro pela metade
![image](https://user-images.githubusercontent.com/83819836/230248527-7903f865-019d-4cc2-b1d4-fa21413a5cbe.png)
### Para acharmos a distância entre os dois círculos, precisamos primeiro *achar a diferença entre suas posições X e Y ( x2-x1 e y2-y1)*, assim, achando os 2 *catetos e formando um triangulo faltando a Hipotenusa*, que pode ser descoberta utilizando o Teorema de Pitágoras ( C² + C² = H² ), ou seja, DiferençaX² + DiferençaY² = Distância²
![image](https://user-images.githubusercontent.com/83819836/230249506-d73cdaa0-ee6e-4088-8336-b8eb36214cf6.png)
### Caso a *soma dos raios seja menor ou igual a hipotenusa*, significa que os círculos estão colidindo

# Prévia
![image](https://user-images.githubusercontent.com/83819836/230249960-1bb3d1d0-abd0-4dd1-a3ff-c0ff44317b96.png)
### Círculo Laranja: Você
### Círculo Azul: outro círculo aleatório
### Círculo na ponta: indicador de colisão (vermelho quando falso, verde quando verdadeiro)
### Textos: informações gerais

# Acesse o site
### Para testar o site, é só acessar o link https://luciano655dev-verifycollision

# Finalização
### Obrigado por ler até aqui! Sinta-se livre para amndar qualquer Pull Request ou contribuir com o projeto, até mais
