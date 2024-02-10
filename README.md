#Comandos
pip install virtualenv

#Criar um ambiente virtual
py -m venv .venv

#Activar o ambiente virtual
.venv\Scripts\activate

#Instalar o pylint(analisador de código estático para Python 2 ou 3)

pip3 install pylint


pylint --generate-rcfile > .pylintrc


pip3 install pre-commit


pre-commit install

#Cria um arquivo contendo todas as configurações e todas as   bibliotecas do nosso projeto
.venv/Scripts/pip3 freeze > requirements.txt

#Instalar o servidor Flask
pip3 install Flask


#Instalar o python-barcode
pip3 install python-barcode 

pip3 install pillow


#Para rodar o servidor
python run_raw.py