# DeteccaoFacialHC - HaarCascade

Resumo

Hoje, mesmo que a IA seja um topico relativamente recente (levando em conta o avanco exponencial do setor de tecnologia no mundo nas ultimas 5 decadas) e apenas "cortejada" como topico futurista em filmes como Matrix a alguns anos, ela ja esta presente e ao nosso redor. Independende do nicho de atuacao esta ajudando organizacoes a prestarem melhores servicos, um deles, o que vou abordar aqui, a Visao Computacional um dos bracos da inteligencia artificial.

A Visao Computacional (CV) esta presente em cameras de seguranca, identificadores de produtos, servico policial e etc, e ja constitui parte importante (e talvez essencial) do funcionamento de alguns sistemas do nosso dia-a-dia. Este simples projeto e apenas o reconhecimento facial atraves de uma webcam comum.

=> Uso:

O projeto esta pronto para uso e reconhecimento facial, basta ter a biblioteca OpenCV instalada, uma webcam e executar o arquivo facial.py.

python facial.py

Para a instalacao da biblioteca OpenCV caso nao tenha, entre no seu Terminal de Comando e digite:

pip install opencv-python

Espere terminar de baixar, e tente novamente. Tambem e possivel fazer a deteccao de outros objetos, desde que voce tenha colocado o arquivo haarcascade (xml) consigo. Sinta-se livre para fazer as alteracoes necessarias. Coloque o seu xml na pasta recursos, e altere a referencia na linha:

classificador = cv2.CascadeClassifier("recursos/haarcascade_frontalface_default.xml")

para: 

classificador = cv2.CascadeClassifier("recursos/[SEU_HAAR_AQUI]")

=> Lembre-se: Pressionar a tecla "q" para sair.
