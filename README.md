# elixir_phoenix_mix_Ansible_version
ansible role for elixir

Erlang and Elixir

"asdf is an Package Manager"

Install asdf (the package manager) that will be used to handle multiple versions of erlang and elixir.

STEP 1,
Install Ubuntu via Vagarant. 

vagrant init ubuntu/trusty64

vagrant up --provider virtualbox

Refer: https://app.vagrantup.com/ubuntu/boxes/trusty64


STEP 2, Update the IP address in the ansible inventory file. While update the hosts line in site.yml file. 

STEP 3, Run the Ansible Playbook using the bellow command. (-i "inventory or host" file as per your ansible config setup)

ansible-playbook -i /etc/ansible/hosts site.yml 
