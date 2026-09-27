# Desafio-Ransomware-DIO
## -------------------Passo a Passo Desafio Ramsonmware DIO------------------

# Criando arquivo Encriptador
(Utilize o arquivo Encrypter.py)

# Criando o arquivo Descriptador
(Utilize o arquivo Decrypter.py)

# Utilizando o Script

1º Abra Sua VM Kali;

2º Crie um diretório para conter os arquivos **(mkdir + "nome diretório")**;

3º Crie três arquivos, o que será encriptado, o encriptador e o descriptador **(touch + "nome arquivo")**;

4º Faça a inserção dos códigos e informações nos arquivos **(nano + "arquivo")**;

5º Para o uso será necessário ativar a função **venv** do python haja vista que o modulo **pyaes** está desatualizado e para evitar corromper sua máquina atual é mais seguro criar esse ambiente virtual;

6º Para ativar a função **venv** utilize o seguinte arquivo **(Passo 6º.bash)**;

7º Após as configurações basta utilizar **(python encrypter.py)** e o arquivo que você criou para ser encriptado estará criptografado. Para verificar utilize **(cat + "arquivo")**;

8º Para descriptografar o arquivo basta utilizar o **(python decrypter.py)** e o arquivo voltará ao normal;
