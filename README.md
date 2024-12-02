Ao Clonar o Projeto com o comando "git clone" utilizar os seguintes comandos 
"docker-compose build --no-cache" para iniciar os containers e baixar as imagens e Etc.

![image](https://github.com/user-attachments/assets/7203c570-e090-44e1-83d6-ecf8bd006152)

e em seguida "Docker-compose up -d" para rodar em segundo Plano.

![Captura de Tela (4)](https://github.com/user-attachments/assets/6d36e9d6-be5d-4a9c-be6b-9b1e9888337b)

Para ver se os containers estão rodando de maneira correta, utilize o seguinte comando "docker ps" ele listara os containers ativos 

![Capturar](https://github.com/user-attachments/assets/6989cac0-6673-42b5-90e6-1912c10114a9)

As Seguintes aplicaçoes estão rodando:
App Flask: http://localhost:5000 
Grafana: http://localhost:3000 
Maria db: http://localhost:3306
Prometheus: http://localhost:9090 

Ao acessar http://localhost:3000 (Grafana) ira aparecer:

![Capturar2](https://github.com/user-attachments/assets/18785de3-d4f1-4775-b399-f5fa5eae66b8)

Usuario: admin
Senha: admin
Irá Abrir a pagina home:

![Capturar22](https://github.com/user-attachments/assets/7640bf72-bd90-4342-8c2b-72e447933d69)

Basta acessar a pagina Dashboard e irá aparecer a seguinte Dashboard

![Capturar23](https://github.com/user-attachments/assets/41abe758-d236-4101-b881-a2bb359a240a)

Acessando ela, irá mostrar o monitoramento da nossa aplicação Flask, baseada nos logs existentes

![Capturar24](https://github.com/user-attachments/assets/6c6e0a75-54b6-4833-a14b-eb9bd6a958cb)

Para acessar o Data Source, acesse a barra lateral e escolhar o caminho Connection -> Data Source, e irá mostrar 

![Capturar26](https://github.com/user-attachments/assets/ab2b51bb-917e-43f3-9b0e-95ca0fc8d742)
![Capturar27](https://github.com/user-attachments/assets/27aa408e-24d5-450d-9230-ca38671cbd71)

Para acessar a Aplicação Flask:
App Flask: http://localhost:5000 
Irá aparecer a Seguinte Pagina:

![CapturarF1](https://github.com/user-attachments/assets/5e7c6ebd-08f0-4f5c-a996-6dea197831cd)

Ao aparecer clique no canto superior direito em Login:

![CapturarF2](https://github.com/user-attachments/assets/791491e0-7140-47ec-8b51-b6cd6a63bfe2)

Credenciais 
user: admin
password: admin
![CapturarF3](https://github.com/user-attachments/assets/93683515-4bde-4715-8f0c-9df6a03142fb)

Ao Fazer login, prosseguir para a Pagina:
http://localhost:5000/alunomodelview/list/

![CapturarF5](https://github.com/user-attachments/assets/14d9344c-2cf9-48dd-be32-adaf2185d077)

Aqui irá listar os alunos cadastrados, para realizar o cadastro existe duas maneiras, a primeira e mais eficiente:
Pelo postamen: utilizando o Json 
{
    "nome": "Teste",
    "sobrenome": "Teste",
    "turma": "Teste",
    "disciplinas": "Teste1, Teste2"
}

![CapturarF6](https://github.com/user-attachments/assets/1211471c-6a21-4888-bbce-7be556c6427c)

agora basta voltar no http://localhost:5000/alunomodelview/list/
atualizar a Pagina e:

![CapturarF7](https://github.com/user-attachments/assets/b91a4718-e1ae-4c0c-a19b-de8dcb235f6d)

Aqui esta nosso Aluno







