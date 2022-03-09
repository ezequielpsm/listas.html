         
var Km_de_distancia, Tempo_de_viagem, Velocidade_media;


Km_de_distancia = Number(window.prompt('Insira o Km de distancia'));
Tempo_de_viagem = Number(window.prompt('insira o tempo de viagem'));
Velocidade_media = Km_de_distancia / Tempo_de_viagem;
if (Velocidade_media <= 80) {
  window.alert('a baixo da velocidade');
} else if (Velocidade_media > 80) {
  window.alert('Acima da Velocidade');
