# Sistema de Apostas

Projeto desenvolvido para a disciplina de Desenvolvimento de Aplicativos Web.
O objetivo do site é possibilitar a aposta nos jogos do mundial do LOL

## Parte 1 (Administrador):
1. Realizar o cadastro de novos jogadores com seus nomes, logins (únicos) e senhas. Cada novo jogador receberá automaticamente um crédito de 100,00 AO.
2. Cadastrar equipes.
3. Registrar as partidas.
4. Definir os resultados das partidas.
5. Adicionar crédito aos jogadores.

## Parte 2 (Público):
1. Permitir que os jogadores façam login.
2. Após o login, exibir o nome do jogador, o valor disponível para apostas e a lista de todas as partidas cadastradas.
3. Permitir que os jogadores selecionem e apostem em uma partida (Apenas uma aposta por jogador por partida. Cada aposta tem o valor fixo de 5,00 AO).
4. Distribuir o prêmio (total do montante de apostas) usando o seguinte critério:
    - O vencedor será aquele que acertar o resultado. Se mais de um jogador acertar o resultado, o prêmio será dividido igualmente entre eles.
    - Se nenhum jogador acertar o resultado, o dinheiro será devolvido para cada jogador.
5. Listar o ranking dos jogadores cadastrados ordenados pelos valores ganhos.
6. Permitir o cadastro de novos jogadores.

## Tabelas Necessárias:
1. Usuários
2. Crédito
3. Equipes
4. Partidas
5. Apostas
6. Ranking

### Tecnologias Utilizadas:
- Python
- Django
- Bootstrap
- JavaScript

## Usabilidade:
1. Instale as dependências do projeto com o comando `pip install -r requirements.txt`.
2. Execute as migrações do banco de dados com os comandos `python manage.py makemigrations` e `python manage.py migrate`.
3. Crie um superusuário com o comando `python manage.py createsuperuser`.
4. Inicie o servidor com o comando `python manage.py runserver`.
5. Acesse o sistema através do endereço `http://localhost:8000` ou `http://127.0.0.1:8000/`.

## Requisitos:
**Cadastro/Login**
1. Criar conta do usuário
2. Mudança de senha

**Apostas**
1. Criar apostas
2. Ver times e partidas
3. Dinheiro apostado
4. Dinheiro sacado

## História de usuário:
**Apostas**
* Eu como usuário de apostas e jogador do jogo league of legends, gostaria muito de poder conseguir apostar no meu time preferido e ganhar um dinheiro em cima disso.
* Eu como admin gostaria de ver e anunciar os jogos que estão acontecendo e que vão acontecer.
* Eu como usuário gostaria de saber a maneira que receberei meu dinheiro após o jogo.

**Usuário**
* Eu como usuário gostaria de maior facilidade e segurança na criação de minha conta.

**Seleção de jogos**
* Eu como usuário apostador gostaria de verificar quais são os tipos de aposta que tenho e os jogos disponíveis.
* Eu como usuário gostaria de saber o valor mínimo do jogo antes de selecionar um.
* Eu como usuário gostaria de saber quais jogos estão disponíveis e o limite para apostar.

**Caso de uso**

![image](https://github.com/desenvolvimento-web-unifil/02-documentacao-unifree/assets/82620144/dcfa014b-902f-49cb-a154-add259274b61)
