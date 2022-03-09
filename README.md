 Exercicio 1 
 
var Km_de_distancia, Tempo_de_viagem, Velocidade_media;


Km_de_distancia = Number(window.prompt('Insira o Km de distancia'));
Tempo_de_viagem = Number(window.prompt('insira o tempo de viagem'));
Velocidade_media = Km_de_distancia / Tempo_de_viagem;
if (Velocidade_media <= 80) {
  window.alert('a baixo da velocidade');
} else if (Velocidade_media > 80) {
  window.alert('Acima da Velocidade');

Exercicio 2

valor_da_compra = None
C_C3_B3digo = None
Valor_com_Desconto = None

def text_prompt(msg):
  try:
    return raw_input(msg)
  except NameError:
    return input(msg)


valor_da_compra = text_prompt('Digite o valor da compra')
C_C3_B3digo = float(text_prompt('Digite o codigo'))
if C_C3_B3digo == 5:
  Valor_com_Desconto = valor_da_compra - valor_da_compra * (10 / 100)
elif C_C3_B3digo == 6:
  Valor_com_Desconto = valor_da_compra - valor_da_compra * (20 / 100)
elif C_C3_B3digo == 7:
  Valor_com_Desconto = valor_da_compra - valor_da_compra / (5 / 100)
print('O desconto é de R$' + str(Valor_com_Desconto))

valor_da_compra
