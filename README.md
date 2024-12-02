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






