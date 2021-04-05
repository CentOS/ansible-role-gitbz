## Ansible Role: gitbz
This gitbz role is used in the CentOS Infra.

It surely depends (see dependencies below) on some other roles.

See also [ansible-infra-playbooks](https://github.com/CentOS/ansible-infra-playbooks) directory to see how the tree/structure is organized

### Variables
See [defaults variables and explanations](defaults/main.yml)
The `gitlab_runner_registration_token` must be overridden with a valid token.

### Dependencies
This role requires [riemers.gitlab-runner](https://galaxy.ansible.com/riemers/gitlab-runner) from Ansible Galaxy.
  * Install it with `ansible-galaxy role install -r meta/requirements.yml`

### License
MIT (see [LICENSE](LICENSE) file)

