# Desafio Técnico QA - Automação 4Devs
Tecnologias Utilizadas
Framework: Robot Framework

Bibliotecas: SeleniumLibrary, Collections

Linguagem: Python

Critérios da Automação
O script segue os seguintes critérios de negócio:

Acessar a página de "Gerador de CPF".

Marcar a opção para não gerar pontuação.

Gerar CPFs em loop até encontrar um que inicie com '7'.

Acessar a página "Gerador de CEP".

Selecionar o estado AM e a cidade Manaus.

Gerar 25 CEPs.

Ao final, verificar e logar no console quais bairros apareceram mais de uma vez.

Como Executar
Clone este repositório.

(Opcional, mas recomendado) Crie um ambiente virtual: python -m venv venv

Instale as dependências: pip install robotframework robotframework-selenium

Execute o teste: robot teste_4devs.robot