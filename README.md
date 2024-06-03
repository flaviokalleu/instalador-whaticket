## Vamos instalar?

FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/flaviokalleu/instalador-whaticket && sudo chmod -R 777 ./instalador-whaticket && cd ./instalador-whaticket && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && cd ./instalador-whaticket && sudo ./install_instancia
```


## Para Instalação você precisa:

Uma VPS Ubuntu 20.04 (Configuração recomendada: 3 VCPU's + 4 GB RAM)

Subdominio para Frontend

Subdominio para API - backoffice

Email válido para certificação SSL
