Aplicação execuável para predição de Faturamento baseado em tabela .csv

Instalar Biblioteca PyQt5

pip install PyQt5

Converter Projeto .Ui (QTDesign) para python

/diretorio_do_frame/ pyuic5 'nomedoframe'.ui -o 'nomedoframe'.py -x

Converter Imagem para Python

/diretorio_da_imagem/ pyrcc5 'nomedaimagem'.qrc -o 'nomedaimagem'.py

Tornar programa executável

pip3 install py installer

/diretorio_do_arquivo/ pyinstaller --onefile --noconsole 'nome_do_arquivo'.py

Se der erro de chamada ( pyinstaller não existe) ( Adicionar o caminho HOME ao Path ) export PATH="$HOME/.local/bin:$PATH"

##############    Utilização do Software     #################

- Ao abrir o Software carregar a tabela de faturamento df.csv 
- Escolher o tipo de Predição no radio button
- Aplicar a Predição 
- Ler os dados no lineEdit

###############################################################
