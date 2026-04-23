# festival

Descreva aqui as alterações/correções que fez
Adicionei o dias.html.
No palcos.html tive que adicionar {% url 'concerto' concerto.id %} ao href.
Em festival.urls adicionei uma rota: path('dias/', views.dias_view, name="dias").
No views.py tive quea adicionar um import do Dia e Palco. Na var concerto coloquei = Concerto.objects.get(id=id).
Adicionei o palcos_view.