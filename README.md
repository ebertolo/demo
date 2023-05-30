# Instruções para configurar arquivo config.ini
Crie um arquivo config.ini e na pasta onde estão os ETLS (Jupyter Notebooks).
O arquivo precisa ter a seguinte estrutura de chaves:
'''
[BancoDeDados]
Servidor = localhost
Banco = NomeDoBancoDeDados
Usuario = usuario
Senha = senha
'''
Substitua localhost pelo IP ou Nome do Servidor SQLServer,  NomeDoBancoDeDados pelo nome do banco de Dados.
E troque usuario e senha pelo usuário e senha do SQL User com permissão de escrita no banco escolhido para rodar os ETLs.

# Notebooks
Os ETLs estão na pasta Notebooks, execute os na seguinte ordem ....

# [Titulo....]
[colocar as demais instruções
