# Lab1-DeepPavlov-
запускаем сначала данную строчку:
from deeppavlov import build_model

model = build_model('squad_bert', download=True) 

затем подставляем свою модель вида:
model(['текст'], ['вопрос по тексту'])
