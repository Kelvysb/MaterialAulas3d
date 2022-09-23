## Aula 28 - Baking

<img src="https://raw.githubusercontent.com/Kelvysb/MaterialAulas3d/master/aula27-28/Chair13.png" height="600px"/>

1. No menu lateral de Render.
2. Alteraremos o render de Eevee para Cycle, pois o Eevee ainda não da suporte a baking.
3. Na aba Sampling / Render.
4. Vamos reduzir o Max Samples para 100, por questões de eficiência, outros valores maiores podem ser testados dependendo do poder da placa de video.
5. Por fim criaremos uma Image texture e criaremos uma imagem chamada 'TextureBaking', esta image texture será o destino de nossas texturas.

<img src="https://raw.githubusercontent.com/Kelvysb/MaterialAulas3d/master/aula27-28/Chair14.png" height="600px"/>

1. Para poder salvar a imagem alteraremos este painel para 'image view'.
2. E selecionaremos a imagem que criamos anteriormente 'TextureBaking'.

<img src="https://raw.githubusercontent.com/Kelvysb/MaterialAulas3d/master/aula27-28/Chair15.png" height="600px"/>

1. Primeiro selecionaremos o tipo do mapa, no caso selecionaremos primeiro o 'Diffuse' que representa o base color de nossa textura.
2. Na aba influence, desmarcaremos a Direct, e Indirect, para a luz não influenciar no baking.
3. Na aba Margin mudaremos o tamanho da margem para 4px.
4. para iniciar o baking selecionamos o Image Texture.
5. E também selecionamos o objeto.
6. Por fim clicamos em Bake.

<img src="https://raw.githubusercontent.com/Kelvysb/MaterialAulas3d/master/aula27-28/Chair16.png" height="600px"/>

1. Caso ainda esteja lento o processo de baking, podemos voltar na aba Sampling.
2. na sub-aba Render.
3. Podemos alterar os valores de max sampling, aumentando diminuímos a velocidade porem aumentamos a qualidade, diminuindo reduziremos a qualidade porem aumentaremos a velocidade.

<img src="https://raw.githubusercontent.com/Kelvysb/MaterialAulas3d/master/aula27-28/Chair17.png" height="600px"/>

1. ao finalizar o baking poderemos visualizar nossa textura no painel 'Image View'.
2. No menu Image.

<img src="https://raw.githubusercontent.com/Kelvysb/MaterialAulas3d/master/aula27-28/Chair18.png" height="600px"/>

1. Podemos salvar nossa textura,

<img src="https://raw.githubusercontent.com/Kelvysb/MaterialAulas3d/master/aula27-28/Chair19.png" height="600px"/>

1. Agora podemos repetir op procedimento para os demais mapas, como Normal.
2. Roughness, e outros como Glossy.



