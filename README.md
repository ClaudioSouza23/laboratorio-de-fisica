# Laboratório de Física

Simulações 3D interativas e material de estudo de física para o ensino médio, para usar em sala e em casa.

Site: https://claudiosouza23.github.io/laboratorio-de-fisica/

## Mecânica

### Dinâmica
Trilha em cinco passos, intercalando teoria e prática:

1. **Resumo, Parte 1** (`dinamica.html#parte1`): força, resultante, inércia e leis de Newton, tipos de força.
2. **Simulação: forças no plano horizontal** (`forcas.html`): inércia, 2ª lei, atrito estático e cinético, força inclinada, ação e reação.
3. **Resumo, Parte 2** (`dinamica.html#parte2`): decomposição de forças, força inclinada no plano horizontal, plano inclinado e método de resolução.
4. **Simulação: plano inclinado com atrito** (`plano-inclinado.html`): decomposição do peso, descida, subida e experimento do ângulo crítico.
5. **Questões de revisão** (`questoes-dinamica.html`): 26 questões com correção na hora e resolução comentada.

## Eletricidade e Magnetismo

Cada tema é uma trilha: resumo → simulações → questões de revisão.

### Eletrostática
- **Resumo** (`eletrostatica.html`): carga elétrica, eletrização, lei de Coulomb, campo elétrico, potencial elétrico e condutores em equilíbrio.
- **Simulação: eletrização por contato** (`contato.html`): três esferas idênticas; contatos, aterramento e conservação da carga.
- **Simulação: Coulomb e campo elétrico** (`coulomb.html`): força entre duas cargas, linhas de campo, mapa de potencial e medição de E e V em qualquer ponto.
- **Questões de revisão** (`questoes-eletrostatica.html`): 19 questões com correção na hora e resolução comentada.

### Eletrodinâmica
- **Resumo** (`eletrodinamica.html`): corrente, potencial elétrico e tensão, resistência e leis de Ohm, associações de resistores, potência e consumo de energia.
- **Simulação: secador de cabelo** (`secador.html`): por que a posição quente tem a menor resistência quando a tensão da tomada é fixa (P = U²/R).
- **Simulação: duas lâmpadas** (`lampadas.html`): as mesmas lâmpadas em paralelo (mesma tensão) e em série (mesma corrente).
- **Questões de revisão** (`questoes.html`): 17 questões com correção na hora e resolução comentada.
- **Jogo em grupo: Trilha da Energia** (`trilha-da-energia.html`, imagem em `img/trilha-da-energia.jpg`): jogo de tabuleiro para a sala (3º ano: potência, consumo, 1ª Lei de Ohm e questões no estilo ENEM). O computador do professor no projetor é a mesa e abre uma sala com QR code; cada equipe entra pelo celular, escolhe a equipe e joga o dado na sua vez. A conexão entre os aparelhos usa PeerJS (WebRTC), sem conta. Também funciona num aparelho só, sem abrir sala. Na configuração, a opção **Cartas físicas na mesa** troca o sorteio pela carta impressa: a equipe pega a carta da cor da casa e digita o código (ex.: P 47) no celular dela ou na mesa, e a pergunta aparece na tela. Os códigos são os mesmos do PDF de cartas com código gerado pelo `gera_leitor.py`.

Magnetismo, outros temas de Mecânica, Termologia, Óptica, Ondulatória e Física Moderna: material em preparação.

As páginas precisam de internet para carregar a biblioteca 3D (three.js).
