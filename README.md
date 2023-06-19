# Apostas-WebApp       
     Este é um sistema desenvolvido em Python utilizando a web Framework Django

<h2>Sistema de apostas</h2>
<p>Projeto desenvolvido para matétia de desenvolvimento de aplicativos web
</p>

## Parte 1 (Voltada para o Administrador):
1. Cadastrar novos jogadores com seus nomes, logins (únicos) e senhas. Cada novo jogador receberá automaticamente um crédito de 10,00 AO.
2. Cadastrar equipes.
3. Cadastrar partidas.
4. Definir os resultados das partidas.
5. Adicionar crédito aos jogadores.

## Parte 2 (Voltada para o Público):
1. Permitir que um jogador faça login.
2. Após o login, exibir o nome do jogador, o valor disponível para apostas e a lista de todas as partidas cadastradas.
3. Permitir que um jogador selecione e aposte em uma partida (Apenas uma aposta por jogador por partida. Cada aposta tem o valor fixo de 5,00 AO).
4. Distribuir o prêmio (total do montante de apostas) usando o seguinte critério:
    - O vencedor será aquele que acertar o resultado. Se mais de um jogador acertar o resultado, o prêmio será dividido igualmente entre eles.
    - Se ninguém acertar o resultado, o dinheiro será devolvido para cada jogador.
5. Listar o ranking dos jogadores cadastrados ordenados pelos valores ganhos.
6. Cadastrar jogador

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

<h2>Usuablidade :</h2>
    <h3>Em ordem de ver o projecto execute os comandos abaixos</h3>
    pip install -r requiriments.txt
    python manage.py makemigrations
    python manage.py migrate
    python manage.py createsuperuser
    python manage.py runserver
    http://localhost:8000 or http://127.0.0.1:8000/
