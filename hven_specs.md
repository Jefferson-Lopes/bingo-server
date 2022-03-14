# Comentários sobre Hven

### JupyterHub

#### Resumo:
Serviço JUPYTERHuB acessível por endereço IP fixo com algum método de autenticação sensato e ligado aos usuários autenticados localmente, que pode oferecer núcleos pré-definidos com serviços e ambientes limitados adequados a cada trabalho. (Com ou sem GPU, limitação de kernels ou memória)

#### Recursos
- https://opendreamkit.org/2018/10/17/jupyterhub-docker/
- https://github.com/jupyterhub/jupyterhub-deploy-docker
- https://medium.com/analytics-vidhya/jupyterhub-docker-31b7a3469872
- https://hub.docker.com/r/jupyterhub/jupyterhub/
- https://jupyterhub.readthedocs.io/en/stable/quickstart-docker.html


### NGINX

#### Resumo
- Proxy reverso escutando :80 e :443 e redirecionando as chamadas para os serviços necessários.

#### Recursos
- https://phoenixnap.com/kb/docker-nginx-reverse-proxy
- https://conzatech.com/configurando-o-nginx-como-proxy-reverso-no-docker/
- https://adamtheautomator.com/nginx-reverse-proxy-docker/

### Wordpress

#### Resumo
- NGINX + Let´s Encrypt + MySQL + PHPfpm +  phpMyAdmin + Wordpress
- Volume mount
- Backup Portal BINGO em um deploy
- Portal BINGO deveveloper version em outro deploy

Várias imagens docker para servir portal. Um backup local do portal BINGO e uma versão do portal para desenvolvimento, que devem ficar rodando continuamente e a possibilidade de criar outros portais de maneira programática rodando outra instância do container com dados montados permanentemente e acessíveis de fora do container.

#### Recursos
- https://www.digitalocean.com/community/tutorials/how-to-install-wordpress-with-docker-compose-pt
- https://medium.com/@habibridho/how-to-easily-setup-wordpress-using-docker-a798081dc577

### Docker Dashboard

#### Resumo:
Esta é uma ferramenta avançada que poderia permitir o gerenciamento das diferentes imagens e containers disponíveis em HVEN com uma interface gráfica, diminuindo a dificuldade do uso de CLIs e melhorando a segurança das operações.

#### Recursos:
- https://docs.docker.com/desktop/dashboard/

### Python Dash

- Docker + Python + F
