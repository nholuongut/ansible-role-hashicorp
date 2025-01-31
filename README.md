# Installation of [HashiCorp](https://www.hashicorp.com/) suite of tools.

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

Requirements
------------

TODO

Role Variables
--------------

* hashicorp_atlas_upload_install: true
* hashicorp_atlas_upload_version: 0.2.0
* hashicorp_consul_install: true
* hashicorp_consul_version: 0.7.2
* hashicorp_consul_daemon_install: false
* hashicorp_consul_daemon_datacenter: "New_England"
* hashicorp_consul_replicate_install: true
* hashicorp_consul_replicate_version: 0.2.0
* hashicorp_consul_template_install: true
* hashicorp_consul_template_version: 0.16.0
* hashicorp_docker_base_install: false
* hashicorp_docker_base_version: 0.0.0
* hashicorp_docker_basetool_install: false
* hashicorp_docker_basetool_version: 0.0.0
* hashicorp_envconsul_install: true
* hashicorp_envconsul_version: 0.6.1
* hashicorp_nomad_install: true
* hashicorp_nomad_version: 0.5.1
* hashicorp_otto_install: false
* hashicorp_otto_version: 0.2.0
* hashicorp_packer_install: true
* hashicorp_packer_version: 0.12.1
* hashicorp_serf_install: true
* hashicorp_serf_version: 0.8.0
* hashicorp_terraform_install: true
* hashicorp_terraform_version: 0.8.2
* hashicorp_vagrant_install: true
* hashicorp_vagrant_version: 1.9.1
* hashicorp_vault_install: true
* hashicorp_vault_version: 0.6.4
* hashicorp_vault_ssh_helper_install: true
* hashicorp_vault_ssh_helper_version: 0.1.2

Dependencies
------------

* kurron.base

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.hashicorp, hashicorp_otto_install: false, hashicorp_consul_version: 0.7.0 }
```

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
