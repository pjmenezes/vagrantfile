# Desafio - DIO

Para este desafio utilizei o Infraestrutura como Código (IaC) - [Vanguard](https://www.modbusdriver.com/diagslave.html). 
* Neste laboratório não foi utilizado com [VirtualBox](https://www.virtualbox.org/), mas sim o KVM. 


# Vagrant Swarm cluster

Execute um cluster Swarm localmente usando o [Vanguard](https://www.modbusdriver.com/diagslave.html), isso criará e configurará 2 máquinas Vagrant em uma rede privada: private_network

* Swarm node 1 (master):10.10.10.100
* Swarm node 2 (node01): 10.10.10.101

As imagem utilizadas foram do: [generic/ubuntu1804](https://app.vagrantup.com/generic/boxes/ubuntu1804)

# Para utilizar

```
$ git clone https://github.com/pjmenezes/vagrantfile.git
$ cd vagrant
$ vagrant up --provider=libvirt
```
