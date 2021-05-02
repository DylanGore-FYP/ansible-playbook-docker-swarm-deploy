# ansible-playbook-docker-swarm-deploy

<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=for-the-badge)](#contributors)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/DylanGore-FYP/ansible-playbook-docker-swarm-deploy/lint-playbook?label=Lint&logo=github&style=for-the-badge)](https://github.com/DylanGore-FYP/ansible-playbook-docker-swarm-deploy/actions/workflows/lint.yml)

An Ansible Playbook that performs initial server setup, installs Docker and configures a Docker Swarm cluster.

## Running

Please create an `inventory` file based on the included example file. You should also create a `vars/vars.yaml` file based on the example variables file.

Get the required roles by running:

```bash
ansible-galaxy install -r requirements.yml -p roles --force
```

Run the playbook:

```bash
ansible-playbook -i inventory playbook.yml
```

## Commit Message Convention

This project uses [Gitmoji](https://gitmoji.dev/) for commit organisation. For more details see the [Gitmoji Repository](https://github.com/carloscuesta/gitmoji).

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/DylanGore"><img src="https://avatars.githubusercontent.com/u/2760449?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Dylan Gore</b></sub></a><br /><a href="https://github.com/DylanGore-FYP/ansible-playbook-docker-swarm-deploy/commits?author=DylanGore" title="Code">💻</a> <a href="https://github.com/DylanGore-FYP/ansible-playbook-docker-swarm-deploy/commits?author=DylanGore" title="Documentation">📖</a> <a href="#ideas-DylanGore" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/mohittaneja7"><img src="https://avatars.githubusercontent.com/u/4126813?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Mohit Taneja</b></sub></a><br /><a href="#ideas-mohittaneja7" title="Ideas, Planning, & Feedback">🤔</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification.
