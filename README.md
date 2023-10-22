# Configuração de Banco de Dados MySQL na Azure e Integração com Power BI

Este guia descreve os passos necessários para configurar um servidor de banco de dados MySQL na Microsoft Azure, popular o servidor com um script e integrá-lo com o Microsoft Power BI. Certifique-se de ter uma conta da Azure e o Microsoft Power BI Desktop instalado antes de prosseguir.

## Passo 1: Criar um Servidor MySQL na Microsoft Azure

1. Faça login na sua conta da Microsoft Azure.

2. No portal da Azure, clique em "Criar um recurso" e procure por "Banco de Dados MySQL".

3. Siga as instruções para configurar o servidor, incluindo nome, senha e configurações de segurança.

4. Anote as informações de conexão, como o nome do servidor e a porta.

## Passo 2: Popular o Servidor com um Script

1. Crie um arquivo SQL contendo os comandos SQL necessários para popular o banco de dados. Por exemplo, um arquivo `populacao.sql`.

2. Faça o upload deste arquivo para a sua instância do servidor MySQL na Azure.

3. Conecte-se ao servidor MySQL usando um cliente SQL (como o MySQL Workbench) e execute o script SQL para popular o banco de dados.

## Passo 3: Integração com o Microsoft Power BI

1. Abra o Microsoft Power BI Desktop.

2. Clique em "Obter Dados" e selecione "Banco de Dados MySQL".

3. Preencha as informações de conexão, como nome do servidor, porta, nome do banco de dados, nome de usuário e senha.

4. Clique em "Conectar" e escolha as tabelas que deseja importar para o Power BI.

5. Realize as transformações de dados necessárias no Power Query Editor.

6. Crie seus relatórios e visualizações no Power BI Desktop.

7. Publique seu relatório no Power BI Service para compartilhá-lo com outras pessoas.

## Passo 4: Realizar as Transformações Indicadas

Para realizar transformações de dados no Power BI, siga estes passos:

1. Na janela de consulta, clique com o botão direito na tabela que deseja transformar.

2. Selecione "Editar Consulta" para abrir o Power Query Editor.

3. Use as ferramentas disponíveis no Power Query Editor para realizar as transformações desejadas, como limpeza de dados, junção de tabelas, criação de colunas calculadas, etc.

4. Clique em "Fechar e Aplicar" para salvar as transformações.

## Conclusão

Com este guia, você configurou um servidor de banco de dados MySQL na Microsoft Azure, populou-o com um script e integrou-o com o Microsoft Power BI. Agora você pode criar relatórios e visualizações a partir dos dados do seu banco de dados.

Lembre-se de manter as informações de segurança, como senhas, protegidas e de acordo com as práticas recomendadas de segurança de dados.

Aproveite a integração de dados e análises fornecida pela Azure e pelo Power BI!
