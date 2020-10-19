# Treinamento Descomplica o Ansible

Instalando um Cluste k8s com Ansible

## Fases do Projeto
- Provisioning      ==> Criando as instancias na AWS
- install k8s       ==> Criando um Cluster na AWS
- Deploy_app_01     ==> Deploy de uma aplicação exemplo
- Deploy_app_02     ==> Deploy da segunda aplicação com destroy do primeiro app_v1

## Antes, instale estes complementos via pip ou pip-3

- pip-3 install boto
- pip-3 install boto3
- pip-3 install botocore

### Install colection via galaxy 

- ansible-galaxy collection install community.kubernetes


## License
[MIT](https://choosealicense.com/licenses/mit/)
