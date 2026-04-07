Documentação do Sistema de Controle de Ferramentas
Descrição
Este sistema permite o cadastro, consulta e gerenciamento de ferramentas utilizadas pela empresa. A interface gráfica foi desenvolvida com Tkinter, utilizando banco de dados SQLite. O sistema suporta leitura de QR Code para facilitar o preenchimento dos dados e busca automática das informações da ferramenta.

Funcionalidades
Cadastro de Ferramentas:
Preencha os campos e clique em "Salvar" para registrar uma nova ferramenta.

Leitura de QR Code:
Clique em "Ler QR Code" para capturar o código via webcam. O campo "Código" será preenchido automaticamente e os dados da ferramenta serão buscados.

Consulta de Ferramentas:
Clique em "Consultar Ferramentas" para visualizar uma lista de todas as ferramentas cadastradas, com nome, código, responsável e situação.

Busca pelo Código:
Digite ou leia o código da ferramenta e clique em "Buscar pelo Código" para preencher todos os campos com as informações cadastradas.

Como Usar
Instalação dos Requisitos

Execute no terminal:

pip install opencv-python pyzbar
Execução

Navegue até a pasta do arquivo app.py:

cd controle-ferramentas\src
Execute o sistema:

python [app.py](http://_vscodecontentref_/0)
Interface





