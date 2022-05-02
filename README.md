# poc-devops-Kubernetes

### Comandos:
vagrant up ; vagrant vbguest --do install --no-cleanup ; vagrant ssh -c 'yes | sudo /mnt/VBoxLinuxAdditions.run'

####################################
### SSH com vagrant /etc/ssh/ssh-config
HOST *
GSSAPIAuthentication yes

## Instalação do VirtaulBox =< 6.0
## Instalação do Vagrant

## Configuração do Vagrant
echo mkdir /home/vagrant/.ssh/
     sudo wget 'https://raw.githubusercontent.com/hashicorp/vagrant/master/keys/vagrant.pub' -P ~/.ssh
     cp -r ~/.ssh/* /home/vagrant/.ssh
     sudo chown -R vagrant /home/vagrant/.ssh
     sudo chmod -R go-rwsx /home/vagrant/.ssh
     
### A Intenção era subir Kubernetes com ansible para chamar as playbook, porém a escolha de usar vagrant me tomou muito tempo para conseguir entender as trocas de chaves.

### A estrutura que seria provissionda seria:

## Infra:
- Kubernetes k8s com Virtual e vagrant

### Monitoramentos:
- Prometheus 
- Alertmanager
- Grafana
- Thanos (Opcional)

### APM:
Kibana stack
 - Elastic search
 - Kibana
 - Logstash
 - Beats
 
### Repositorio:
- Gitalab
 

### CI/CD:
- jenkins devops
- sonarqube
- nexus
- postman
- Newman html extra


