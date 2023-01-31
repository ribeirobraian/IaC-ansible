# IaC-ansible
repositorio de criação de infraestrutura como codigo com ansible.

Caso necessite de consultar um comando no ansible entre em :
www.docs.ansible.com/ansible/2.4/list_of_all_modules.html

configurar arquivo do mysql, copiando ele para uma pasta (sugestão "file"), alterar a linha bind-address = 0.0.0.0

na configuração do apache, arquivo (/files/000-default.conf) procure linha(12) e informe DocumentRoot {{ wp_install_dir }}  

copiar o arquivo (/files/000-default.conf) a uma pasta chamada template
