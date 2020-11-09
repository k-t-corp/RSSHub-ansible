# RSSHub-ansible

Ansible to deploy [RSSHub](https://github.com/DIYgod/RSSHub) on bare-metal


## Usage
On `Ubuntu 20.04`, [install ansible](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-ansible-on-ubuntu-20-04), then

```bash
ansible-playbook rsshub.yaml
```


## Development
Install `vagrant`, then

```bash
./try.sh
ansible-playbook rsshub.yaml
```
