# Sistema de Apostas

Projeto desenvolvido para a disciplina de Desenvolvimento de Aplicativos Web.
Objetivo é apostar os jogosdo mundial do LOL

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
