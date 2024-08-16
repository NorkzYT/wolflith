<p align="center">
    <img src="Docs/content/assets/img/wolflith-cover-rl.png" width="490">
</p>

<p align="center">Streamline Your Docker Deployments with One Command</p>
<div align="center">
  <!-- Contributions Welcome Badge -->
  <a href="CODE_OF_CONDUCT.md" target="_blank">
    <img src="https://img.shields.io/badge/contributions-welcome-brightgreen?logo=github" alt="Contributions Welcome">
  </a>
  <!-- Commits per Month -->
  <a href="https://github.com/NorkzYT/Wolflith/pulse">
    <img src="https://img.shields.io/github/commit-activity/m/NorkzYT/Wolflith" alt="Commits-per-month">
  </a>
  <!-- License Badge -->
  <a href="https://github.com/NorkzYT/Wolflith/blob/main/LICENSE" target="_blank">
    <img src="https://img.shields.io/badge/license-GNUv3-purple" alt="License">
  </a>
  <!-- Contributor Covenant Badge -->
  <a href="https://contributor-covenant.org/version/2/1/code_of_conduct/" target="_blank">
    <img src="https://img.shields.io/badge/Contributor%20Covenant-2.1-purple" alt="Contributor Covenant 2.1">
  </a>
  <!-- Github Stars Badge -->
  <a href="https://github.com/NorkzYT/Wolflith/stargazers" target="_blank">
    <img src="https://img.shields.io/github/stars/NorkzYT/Wolflith" alt="Github Stars">
  </a>
</div>

## About

Wolflith is a revolutionary toolkit crafted to redefine the deployment of Docker containers, enabling both novices and experts to manage docker services efficiently across Linux environments. With a robust foundation in Ansible for seamless orchestration, it offers a remarkably simple yet powerful one-command solution to deploy a diverse array of docker services or even your customized ones, across any number of machines. Designed for the tech enthusiast seeking efficiency without the hassle, Wolflith promises a significant reduction in deployment time and complexity, making it the go-to solution for those dedicated to streamlining their tech stacks in Docker-centric platforms. Experience the ease of managing your digital projects with Wolflith, where simplicity meets functionality.

Note: This repository is in BETA and still a work in progress, I welcome contributions to expand its capabilities and usability.

## How to Install

```bash
sudo wget -qO /opt/PCSInstall.sh https://raw.githubusercontent.com/NorkzYT/Wolflith/main/PCSMenu/PCSInstall.sh
sudo chmod +x /opt/PCSInstall.sh
sudo /opt/PCSInstall.sh --branch="main"
```

## Contributing

Please see the [contributing guide](./CONTRIBUTING.md)

## Credits

Created by NorkzYT with 💛

► Twitch <https://www.twitch.tv/polymathnorkz>

► Discord <https://discord.com/users/282100214024896522>

► GitHub <https://github.com/NorkzYT>

<details>
<summary>Click to expand the repo tree</summary>

<!-- tree generated by repoTree.py starts here -->

- [.env.example](./.env.example)
- [**.github**](./.github)
  - [CODEOWNERS](./.github/CODEOWNERS)
  - [FUNDING.yml](./.github/FUNDING.yml)
  - [**ISSUE_TEMPLATE**](./.github/ISSUE_TEMPLATE)
    - [bug_report.yml](./.github/ISSUE_TEMPLATE/bug_report.yml)
    - [feature_request.yml](./.github/ISSUE_TEMPLATE/feature_request.yml)
  - [PULL_REQUEST_TEMPLATE.md](./.github/PULL_REQUEST_TEMPLATE.md)
  - [**workflows**](./.github/workflows)
    - [changelog.yml](./.github/workflows/changelog.yml)
    - [gitlab-sync.yml](./.github/workflows/gitlab-sync.yml)
    - [lint.yml](./.github/workflows/lint.yml)
    - [release.yml](./.github/workflows/release.yml)
- [.gitignore](./.gitignore)
- [.prettierignore](./.prettierignore)
- [.prettierrc.yaml](./.prettierrc.yaml)
- [.releaserc.json](./.releaserc.json)
- [**.vscode**](./.vscode)
  - [extensions.json](./.vscode/extensions.json)
  - [settings.json](./.vscode/settings.json)
- [**Ansible**](./Ansible)
  - [README.md](./Ansible/README.md)
  - [**adhoc**](./Ansible/adhoc)
    - [adhoc.md](./Ansible/adhoc/adhoc.md)
  - [**collections**](./Ansible/collections)
    - [requirements.yml](./Ansible/collections/requirements.yml)
  - [**inventory**](./Ansible/inventory)
    - [ansible.cfg](./Ansible/inventory/ansible.cfg)
    - [hosts.example.yaml](./Ansible/inventory/hosts.example.yaml)
  - [**playbooks**](./Ansible/playbooks)
    - [1password.yml](./Ansible/playbooks/1password.yml)
    - [ansible-upgrade.yml](./Ansible/playbooks/ansible-upgrade.yml)
    - [apt.yml](./Ansible/playbooks/apt.yml)
    - [binfmt.yml](./Ansible/playbooks/binfmt.yml)
    - [docker-update.yml](./Ansible/playbooks/docker-update.yml)
    - [docker.yml](./Ansible/playbooks/docker.yml)
    - [fail2ban.yml](./Ansible/playbooks/fail2ban.yml)
    - [iftop.yml](./Ansible/playbooks/iftop.yml)
    - [lvm-fix.yml](./Ansible/playbooks/lvm-fix.yml)
    - [oh-my-zsh.yml](./Ansible/playbooks/oh-my-zsh.yml)
    - [password-change.yml](./Ansible/playbooks/password-change.yml)
    - [provision-docker-service.yml](./Ansible/playbooks/provision-docker-service.yml)
    - [provision-proxmox-lxc.yml](./Ansible/playbooks/provision-proxmox-lxc.yml)
    - [qemu-guest-agent.yml](./Ansible/playbooks/qemu-guest-agent.yml)
    - [reboot-required.yml](./Ansible/playbooks/reboot-required.yml)
    - [reboot.yml](./Ansible/playbooks/reboot.yml)
    - [resize-lvm.yml](./Ansible/playbooks/resize-lvm.yml)
    - [run-custom-command.yml](./Ansible/playbooks/run-custom-command.yml)
    - [ssh-get-key.yml](./Ansible/playbooks/ssh-get-key.yml)
    - [timezone.yml](./Ansible/playbooks/timezone.yml)
    - [user-creation.yml](./Ansible/playbooks/user-creation.yml)
    - [zsh.yml](./Ansible/playbooks/zsh.yml)
    - [zsh_powerlevel10k.yml](./Ansible/playbooks/zsh_powerlevel10k.yml)
  - [**static**](./Ansible/static)
    - [.p10k.zsh](./Ansible/static/.p10k.zsh)
    - [addCifsShare.sh](./Ansible/static/addCifsShare.sh)
  - [**templates**](./Ansible/templates)
    - [timesyncd.conf](./Ansible/templates/timesyncd.conf)
- [**Auto**](./Auto)
  - [dependencies.sh](./Auto/dependencies.sh)
  - [environmentSetup.sh](./Auto/environmentSetup.sh)
  - [modifyComposeFiles.sh](./Auto/modifyComposeFiles.sh)
  - [setup.sh](./Auto/setup.sh)
- [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)
- [CONTRIBUTING.md](./CONTRIBUTING.md)
- [**Docker**](./Docker)
  - [**AMD64**](./Docker/AMD64)
    - [**appflowy**](./Docker/AMD64/appflowy)
      - [.env.example](./Docker/AMD64/appflowy/.env.example)
      - [docker-compose.yml](./Docker/AMD64/appflowy/docker-compose.yml)
    - [**browserless**](./Docker/AMD64/browserless)
      - [.env.example](./Docker/AMD64/browserless/.env.example)
      - [docker-compose.yml](./Docker/AMD64/browserless/docker-compose.yml)
    - [**discord**](./Docker/AMD64/discord)
      - [.env.example](./Docker/AMD64/discord/.env.example)
      - [docker-compose.yml](./Docker/AMD64/discord/docker-compose.yml)
    - [**docker-osx**](./Docker/AMD64/docker-osx)
      - [.env.example](./Docker/AMD64/docker-osx/.env.example)
      - [docker-compose.yml](./Docker/AMD64/docker-osx/docker-compose.yml)
    - [**dupeguru**](./Docker/AMD64/dupeguru)
      - [.env.example](./Docker/AMD64/dupeguru/.env.example)
      - [docker-compose.yml](./Docker/AMD64/dupeguru/docker-compose.yml)
    - [**gitlab**](./Docker/AMD64/gitlab)
      - [.env.example](./Docker/AMD64/gitlab/.env.example)
      - [docker-compose.yml](./Docker/AMD64/gitlab/docker-compose.yml)
    - [**guacd**](./Docker/AMD64/guacd)
      - [docker-compose.yml](./Docker/AMD64/guacd/docker-compose.yml)
    - [**krusader**](./Docker/AMD64/krusader)
      - [.env.example](./Docker/AMD64/krusader/.env.example)
      - [docker-compose.yml](./Docker/AMD64/krusader/docker-compose.yml)
    - [**meshcentral**](./Docker/AMD64/meshcentral)
      - [.env.example](./Docker/AMD64/meshcentral/.env.example)
      - [docker-compose.yml](./Docker/AMD64/meshcentral/docker-compose.yml)
    - [**pwm**](./Docker/AMD64/pwm)
      - [docker-compose.yml](./Docker/AMD64/pwm/docker-compose.yml)
    - [**shinpuru**](./Docker/AMD64/shinpuru)
      - [.env.example](./Docker/AMD64/shinpuru/.env.example)
      - [docker-compose.yml](./Docker/AMD64/shinpuru/docker-compose.yml)
    - [**webnut**](./Docker/AMD64/webnut)
      - [.env.example](./Docker/AMD64/webnut/.env.example)
      - [docker-compose.yml](./Docker/AMD64/webnut/docker-compose.yml)
  - [**ARM64**](./Docker/ARM64)
    - [**gitlab**](./Docker/ARM64/gitlab)
      - [.env.example](./Docker/ARM64/gitlab/.env.example)
      - [docker-compose.yml](./Docker/ARM64/gitlab/docker-compose.yml)
    - [**squid-auth**](./Docker/ARM64/squid-auth)
      - [.env.example](./Docker/ARM64/squid-auth/.env.example)
      - [docker-compose.yml](./Docker/ARM64/squid-auth/docker-compose.yml)
  - [**Both**](./Docker/Both)
    - [**1password**](./Docker/Both/1password)
      - [1password-credentials.example.json](./Docker/Both/1password/1password-credentials.example.json)
      - [docker-compose.yml](./Docker/Both/1password/docker-compose.yml)
    - [**1password-gui**](./Docker/Both/1password-gui)
      - [**data**](./Docker/Both/1password-gui/data)
    - [**adminer**](./Docker/Both/adminer)
      - [docker-compose.yml](./Docker/Both/adminer/docker-compose.yml)
    - [**apacheguacamole**](./Docker/Both/apacheguacamole)
      - [.env.example](./Docker/Both/apacheguacamole/.env.example)
      - [docker-compose.yml](./Docker/Both/apacheguacamole/docker-compose.yml)
    - [**authelia**](./Docker/Both/authelia)
      - [.env.example](./Docker/Both/authelia/.env.example)
      - [**config**](./Docker/Both/authelia/config)
        - [configuration.yml](./Docker/Both/authelia/config/configuration.yml)
        - [users_database.yml](./Docker/Both/authelia/config/users_database.yml)
      - [docker-compose.yml](./Docker/Both/authelia/docker-compose.yml)
    - [**authentik**](./Docker/Both/authentik)
      - [.env.example](./Docker/Both/authentik/.env.example)
      - [docker-compose.yml](./Docker/Both/authentik/docker-compose.yml)
    - [**binfmt**](./Docker/Both/binfmt)
      - [docker-compose.yml](./Docker/Both/binfmt/docker-compose.yml)
    - [**bookstack**](./Docker/Both/bookstack)
      - [.env.example](./Docker/Both/bookstack/.env.example)
      - [docker-compose.yml](./Docker/Both/bookstack/docker-compose.yml)
    - [**cloudcmd**](./Docker/Both/cloudcmd)
      - [docker-compose.yml](./Docker/Both/cloudcmd/docker-compose.yml)
    - [**cloudflared**](./Docker/Both/cloudflared)
      - [.env.example](./Docker/Both/cloudflared/.env.example)
      - [**config**](./Docker/Both/cloudflared/config)
        - [config.yaml](./Docker/Both/cloudflared/config/config.yaml)
      - [docker-compose.yml](./Docker/Both/cloudflared/docker-compose.yml)
    - [**codeserver**](./Docker/Both/codeserver)
      - [.env.example](./Docker/Both/codeserver/.env.example)
      - [**Wolflith.code-workspace**](./Docker/Both/codeserver/Wolflith.code-workspace)
      - [docker-compose.yml](./Docker/Both/codeserver/docker-compose.yml)
      - [dockerfile](./Docker/Both/codeserver/dockerfile)
      - [wolflith.code-workspace](./Docker/Both/codeserver/wolflith.code-workspace)
    - [**cryptgeon**](./Docker/Both/cryptgeon)
      - [.env.example](./Docker/Both/cryptgeon/.env.example)
      - [docker-compose.yml](./Docker/Both/cryptgeon/docker-compose.yml)
    - [**dashy**](./Docker/Both/dashy)
      - [.env.example](./Docker/Both/dashy/.env.example)
      - [docker-compose.yml](./Docker/Both/dashy/docker-compose.yml)
    - [**discordchatexporter**](./Docker/Both/discordchatexporter)
      - [.env.example](./Docker/Both/discordchatexporter/.env.example)
      - [docker-compose.yml](./Docker/Both/discordchatexporter/docker-compose.yml)
      - [schedule_discord_exporter.sh](./Docker/Both/discordchatexporter/schedule_discord_exporter.sh)
    - [**docker-socket-proxy**](./Docker/Both/docker-socket-proxy)
      - [docker-compose.yml](./Docker/Both/docker-socket-proxy/docker-compose.yml)
    - [**doublecommander**](./Docker/Both/doublecommander)
      - [.env.example](./Docker/Both/doublecommander/.env.example)
      - [docker-compose.yml](./Docker/Both/doublecommander/docker-compose.yml)
    - [**dozzle**](./Docker/Both/dozzle)
      - [.env.example](./Docker/Both/dozzle/.env.example)
      - [docker-compose.yml](./Docker/Both/dozzle/docker-compose.yml)
    - [**dupeguru**](./Docker/Both/dupeguru)
      - [.env.example](./Docker/Both/dupeguru/.env.example)
      - [docker-compose.yml](./Docker/Both/dupeguru/docker-compose.yml)
    - [**duplicati**](./Docker/Both/duplicati)
      - [.env.example](./Docker/Both/duplicati/.env.example)
      - [docker-compose.yml](./Docker/Both/duplicati/docker-compose.yml)
    - [**endlessh**](./Docker/Both/endlessh)
      - [.env.example](./Docker/Both/endlessh/.env.example)
      - [docker-compose.yml](./Docker/Both/endlessh/docker-compose.yml)
    - [**firefly-iii**](./Docker/Both/firefly-iii)
      - [.env.example](./Docker/Both/firefly-iii/.env.example)
      - [docker-compose.yml](./Docker/Both/firefly-iii/docker-compose.yml)
    - [**flame**](./Docker/Both/flame)
      - [.env.example](./Docker/Both/flame/.env.example)
      - [docker-compose.yml](./Docker/Both/flame/docker-compose.yml)
    - [**floatplane-downloader**](./Docker/Both/floatplane-downloader)
      - [.env.example](./Docker/Both/floatplane-downloader/.env.example)
      - [docker-compose.yml](./Docker/Both/floatplane-downloader/docker-compose.yml)
    - [**gatus**](./Docker/Both/gatus)
      - [.env.example](./Docker/Both/gatus/.env.example)
      - [**config**](./Docker/Both/gatus/config)
        - [config.yaml](./Docker/Both/gatus/config/config.yaml)
      - [docker-compose.yml](./Docker/Both/gatus/docker-compose.yml)
    - [**gitlabrunner**](./Docker/Both/gitlabrunner)
      - [.env.example](./Docker/Both/gitlabrunner/.env.example)
      - [docker-compose.yml](./Docker/Both/gitlabrunner/docker-compose.yml)
    - [**gokapi**](./Docker/Both/gokapi)
      - [docker-compose.yml](./Docker/Both/gokapi/docker-compose.yml)
    - [**grafana**](./Docker/Both/grafana)
      - [docker-compose.yml](./Docker/Both/grafana/docker-compose.yml)
    - [**grocy**](./Docker/Both/grocy)
      - [.env.example](./Docker/Both/grocy/.env.example)
      - [docker-compose.yml](./Docker/Both/grocy/docker-compose.yml)
    - [**homechart**](./Docker/Both/homechart)
      - [.env.example](./Docker/Both/homechart/.env.example)
      - [docker-compose.yml](./Docker/Both/homechart/docker-compose.yml)
    - [**influxdb**](./Docker/Both/influxdb)
      - [.env.example](./Docker/Both/influxdb/.env.example)
      - [docker-compose.yml](./Docker/Both/influxdb/docker-compose.yml)
    - [**invidious**](./Docker/Both/invidious)
      - [.env.example](./Docker/Both/invidious/.env.example)
      - [**config**](./Docker/Both/invidious/config)
        - [**docker**](./Docker/Both/invidious/config/docker)
          - [init-invidious-db.sh](./Docker/Both/invidious/config/docker/init-invidious-db.sh)
        - [**sql**](./Docker/Both/invidious/config/sql)
          - [annotations.sql](./Docker/Both/invidious/config/sql/annotations.sql)
          - [channel_videos.sql](./Docker/Both/invidious/config/sql/channel_videos.sql)
          - [channels.sql](./Docker/Both/invidious/config/sql/channels.sql)
          - [nonces.sql](./Docker/Both/invidious/config/sql/nonces.sql)
          - [playlist_videos.sql](./Docker/Both/invidious/config/sql/playlist_videos.sql)
          - [playlists.sql](./Docker/Both/invidious/config/sql/playlists.sql)
          - [session_ids.sql](./Docker/Both/invidious/config/sql/session_ids.sql)
          - [users.sql](./Docker/Both/invidious/config/sql/users.sql)
          - [videos.sql](./Docker/Both/invidious/config/sql/videos.sql)
      - [docker-compose.yml](./Docker/Both/invidious/docker-compose.yml)
    - [**joplin**](./Docker/Both/joplin)
      - [.env.example](./Docker/Both/joplin/.env.example)
      - [docker-compose.yml](./Docker/Both/joplin/docker-compose.yml)
    - [**kasm**](./Docker/Both/kasm)
      - [docker-compose.yml](./Docker/Both/kasm/docker-compose.yml)
    - [**linkace**](./Docker/Both/linkace)
      - [.env.example](./Docker/Both/linkace/.env.example)
      - [docker-compose.yml](./Docker/Both/linkace/docker-compose.yml)
    - [**linkwarden**](./Docker/Both/linkwarden)
      - [.env.example](./Docker/Both/linkwarden/.env.example)
      - [docker-compose.yml](./Docker/Both/linkwarden/docker-compose.yml)
    - [**littlelinkserver**](./Docker/Both/littlelinkserver)
      - [.env.example](./Docker/Both/littlelinkserver/.env.example)
      - [docker-compose.yml](./Docker/Both/littlelinkserver/docker-compose.yml)
    - [**mariadb**](./Docker/Both/mariadb)
      - [.env.example](./Docker/Both/mariadb/.env.example)
      - [docker-compose.yml](./Docker/Both/mariadb/docker-compose.yml)
    - [**memcached**](./Docker/Both/memcached)
      - [.env.example](./Docker/Both/memcached/.env.example)
      - [docker-compose.yml](./Docker/Both/memcached/docker-compose.yml)
    - [**mongodb**](./Docker/Both/mongodb)
      - [.env.example](./Docker/Both/mongodb/.env.example)
      - [docker-compose.yml](./Docker/Both/mongodb/docker-compose.yml)
    - [**monitorss**](./Docker/Both/monitorss)
      - [.env.example](./Docker/Both/monitorss/.env.example)
      - [docker-compose.yml](./Docker/Both/monitorss/docker-compose.yml)
    - [**n8n**](./Docker/Both/n8n)
      - [.env.example](./Docker/Both/n8n/.env.example)
      - [docker-compose.yml](./Docker/Both/n8n/docker-compose.yml)
    - [**nginx_proxy_manager**](./Docker/Both/nginx_proxy_manager)
      - [.env.example](./Docker/Both/nginx_proxy_manager/.env.example)
      - [docker-compose.yml](./Docker/Both/nginx_proxy_manager/docker-compose.yml)
    - [**node-red**](./Docker/Both/node-red)
      - [.env.example](./Docker/Both/node-red/.env.example)
      - [docker-compose.yml](./Docker/Both/node-red/docker-compose.yml)
    - [**ntp**](./Docker/Both/ntp)
      - [.env.example](./Docker/Both/ntp/.env.example)
      - [docker-compose.yml](./Docker/Both/ntp/docker-compose.yml)
    - [**nut-webgui**](./Docker/Both/nut-webgui)
      - [.env.example](./Docker/Both/nut-webgui/.env.example)
      - [docker-compose.yml](./Docker/Both/nut-webgui/docker-compose.yml)
    - [**ollama**](./Docker/Both/ollama)
      - [docker-compose.yml](./Docker/Both/ollama/docker-compose.yml)
    - [**organizrv2**](./Docker/Both/organizrv2)
      - [.env.example](./Docker/Both/organizrv2/.env.example)
      - [docker-compose.yml](./Docker/Both/organizrv2/docker-compose.yml)
    - [**paperless-ngx**](./Docker/Both/paperless-ngx)
      - [.env.example](./Docker/Both/paperless-ngx/.env.example)
      - [docker-compose.yml](./Docker/Both/paperless-ngx/docker-compose.yml)
    - [**passwordpusher**](./Docker/Both/passwordpusher)
      - [.env.example](./Docker/Both/passwordpusher/.env.example)
      - [docker-compose.yml](./Docker/Both/passwordpusher/docker-compose.yml)
    - [**photoprism**](./Docker/Both/photoprism)
      - [.env.example](./Docker/Both/photoprism/.env.example)
      - [docker-compose.yml](./Docker/Both/photoprism/docker-compose.yml)
    - [**portainer**](./Docker/Both/portainer)
      - [docker-compose.yml](./Docker/Both/portainer/docker-compose.yml)
    - [**postgresql**](./Docker/Both/postgresql)
      - [.env.example](./Docker/Both/postgresql/.env.example)
      - [docker-compose.yml](./Docker/Both/postgresql/docker-compose.yml)
    - [**proxy.py**](./Docker/Both/proxy.py)
      - [.env.example](./Docker/Both/proxy.py/.env.example)
      - [docker-compose.yml](./Docker/Both/proxy.py/docker-compose.yml)
    - [**pterodactyl**](./Docker/Both/pterodactyl)
      - [**pterodactyl-panel**](./Docker/Both/pterodactyl/pterodactyl-panel)
        - [.env.example](./Docker/Both/pterodactyl/pterodactyl-panel/.env.example)
        - [docker-compose.yml](./Docker/Both/pterodactyl/pterodactyl-panel/docker-compose.yml)
      - [**pterodactyl-wings**](./Docker/Both/pterodactyl/pterodactyl-wings)
        - [.env.example](./Docker/Both/pterodactyl/pterodactyl-wings/.env.example)
        - [docker-compose.yml](./Docker/Both/pterodactyl/pterodactyl-wings/docker-compose.yml)
    - [**putty**](./Docker/Both/putty)
      - [.env.example](./Docker/Both/putty/.env.example)
      - [docker-compose.yml](./Docker/Both/putty/docker-compose.yml)
    - [**redis**](./Docker/Both/redis)
      - [docker-compose.yml](./Docker/Both/redis/docker-compose.yml)
    - [**searxng**](./Docker/Both/searxng)
      - [.env.example](./Docker/Both/searxng/.env.example)
      - [docker-compose.yml](./Docker/Both/searxng/docker-compose.yml)
    - [**solr**](./Docker/Both/solr)
      - [docker-compose.yml](./Docker/Both/solr/docker-compose.yml)
    - [**speedtest**](./Docker/Both/speedtest)
      - [.env.example](./Docker/Both/speedtest/.env.example)
      - [docker-compose.yml](./Docker/Both/speedtest/docker-compose.yml)
    - [**squid**](./Docker/Both/squid)
      - [.env.example](./Docker/Both/squid/.env.example)
      - [docker-compose.yml](./Docker/Both/squid/docker-compose.yml)
    - [**syncthing**](./Docker/Both/syncthing)
      - [.env.example](./Docker/Both/syncthing/.env.example)
      - [docker-compose.yml](./Docker/Both/syncthing/docker-compose.yml)
    - [**tailscale**](./Docker/Both/tailscale)
      - [.env.example](./Docker/Both/tailscale/.env.example)
      - [docker-compose.yml](./Docker/Both/tailscale/docker-compose.yml)
    - [**tdarr**](./Docker/Both/tdarr)
      - [.env.example](./Docker/Both/tdarr/.env.example)
      - [docker-compose.yml](./Docker/Both/tdarr/docker-compose.yml)
    - [**traefik**](./Docker/Both/traefik)
      - [.env.example](./Docker/Both/traefik/.env.example)
      - [**config**](./Docker/Both/traefik/config)
        - [acme.json](./Docker/Both/traefik/config/acme.json)
        - [fileConfig.yml](./Docker/Both/traefik/config/fileConfig.yml)
        - [traefik.yml](./Docker/Both/traefik/config/traefik.yml)
      - [docker-compose.yml](./Docker/Both/traefik/docker-compose.yml)
    - [**tubearchivist**](./Docker/Both/tubearchivist)
      - [.env.example](./Docker/Both/tubearchivist/.env.example)
      - [docker-compose.yml](./Docker/Both/tubearchivist/docker-compose.yml)
    - [**ubuntu-desktop**](./Docker/Both/ubuntu-desktop)
      - [.env.example](./Docker/Both/ubuntu-desktop/.env.example)
      - [docker-compose.yml](./Docker/Both/ubuntu-desktop/docker-compose.yml)
    - [**uptimekuma**](./Docker/Both/uptimekuma)
      - [docker-compose.yml](./Docker/Both/uptimekuma/docker-compose.yml)
    - [**vault**](./Docker/Both/vault)
      - [.env.example](./Docker/Both/vault/.env.example)
      - [**config**](./Docker/Both/vault/config)
        - [config.hcl](./Docker/Both/vault/config/config.hcl)
        - [vault.json](./Docker/Both/vault/config/vault.json)
      - [docker-compose.yml](./Docker/Both/vault/docker-compose.yml)
    - [**vwarden**](./Docker/Both/vwarden)
      - [.env.example](./Docker/Both/vwarden/.env.example)
      - [docker-compose.yml](./Docker/Both/vwarden/docker-compose.yml)
    - [**watchtower**](./Docker/Both/watchtower)
      - [.env.example](./Docker/Both/watchtower/.env.example)
      - [docker-compose.yml](./Docker/Both/watchtower/docker-compose.yml)
    - [**webtop**](./Docker/Both/webtop)
      - [.env.example](./Docker/Both/webtop/.env.example)
      - [docker-compose.yml](./Docker/Both/webtop/docker-compose.yml)
    - [**wgeasy**](./Docker/Both/wgeasy)
      - [.env.example](./Docker/Both/wgeasy/.env.example)
      - [docker-compose.yml](./Docker/Both/wgeasy/docker-compose.yml)
    - [**wikijs**](./Docker/Both/wikijs)
      - [.env.example](./Docker/Both/wikijs/.env.example)
      - [docker-compose.yml](./Docker/Both/wikijs/docker-compose.yml)
    - [**windows**](./Docker/Both/windows)
      - [.env.example](./Docker/Both/windows/.env.example)
      - [docker-compose.yml](./Docker/Both/windows/docker-compose.yml)
    - [**wireguard**](./Docker/Both/wireguard)
      - [.env.example](./Docker/Both/wireguard/.env.example)
      - [docker-compose.yml](./Docker/Both/wireguard/docker-compose.yml)
- [**Docs**](./Docs)
  - [FreeForeverOracle.md](./Docs/FreeForeverOracle.md)
  - [**content**](./Docs/content)
    - [**assets**](./Docs/content/assets)
      - [**img**](./Docs/content/assets/img)
        - [wolflith-cover-rl.png](./Docs/content/assets/img/wolflith-cover-rl.png)
    - [wolflith-cover.psd](./Docs/content/wolflith-cover.psd)
- [LICENSE](./LICENSE)
- [Makefile](./Makefile)
- [**PCSMenu**](./PCSMenu)
  - [Cargo.toml](./PCSMenu/Cargo.toml)
  - [PCSInstall.sh](./PCSMenu/PCSInstall.sh)
  - [PCSUpdate.sh](./PCSMenu/PCSUpdate.sh)
  - [**src**](./PCSMenu/src)
    - [Color.sh](./PCSMenu/src/Color.sh)
    - [**Functions**](./PCSMenu/src/Functions)
      - [**Ansible**](./PCSMenu/src/Functions/Ansible)
        - [**Setup Linux Machine**](./PCSMenu/src/Functions/Ansible/Setup%20Linux%20Machine)
          - [setupLinuxMachine.sh](./PCSMenu/src/Functions/Ansible/Setup%20Linux%20Machine/setupLinuxMachine.sh)
        - [**Update Hosts**](./PCSMenu/src/Functions/Ansible/Update%20Hosts)
          - [updateHosts.sh](./PCSMenu/src/Functions/Ansible/Update%20Hosts/updateHosts.sh)
      - [**Docker**](./PCSMenu/src/Functions/Docker)
        - [**Docker Install**](./PCSMenu/src/Functions/Docker/Docker%20Install)
          - [dockerInstall.sh](./PCSMenu/src/Functions/Docker/Docker%20Install/dockerInstall.sh)
        - [**Docker Update**](./PCSMenu/src/Functions/Docker/Docker%20Update)
          - [dockerUpdate.sh](./PCSMenu/src/Functions/Docker/Docker%20Update/dockerUpdate.sh)
        - [**Provision Docker Service**](./PCSMenu/src/Functions/Docker/Provision%20Docker%20Service)
          - [provisionDockerService.sh](./PCSMenu/src/Functions/Docker/Provision%20Docker%20Service/provisionDockerService.sh)
        - [**Scripts**](./PCSMenu/src/Functions/Docker/Scripts)
          - [provisionDockerService.sh](./PCSMenu/src/Functions/Docker/Scripts/provisionDockerService.sh)
          - [selectService.sh](./PCSMenu/src/Functions/Docker/Scripts/selectService.sh)
          - [updateDockerComposeEnv.sh](./PCSMenu/src/Functions/Docker/Scripts/updateDockerComposeEnv.sh)
      - [**Proxmox**](./PCSMenu/src/Functions/Proxmox)
        - [**Provision LXC with Docker Service**](./PCSMenu/src/Functions/Proxmox/Provision%20LXC%20with%20Docker%20Service)
          - [provisionLxcDockerService.sh](./PCSMenu/src/Functions/Proxmox/Provision%20LXC%20with%20Docker%20Service/provisionLxcDockerService.sh)
        - [**Scripts**](./PCSMenu/src/Functions/Proxmox/Scripts)
          - [checkProxmox.sh](./PCSMenu/src/Functions/Proxmox/Scripts/checkProxmox.sh)
          - [provisionLxc.sh](./PCSMenu/src/Functions/Proxmox/Scripts/provisionLxc.sh)
          - [proxmoxLxcCifsShare.sh](./PCSMenu/src/Functions/Proxmox/Scripts/proxmoxLxcCifsShare.sh)
      - [**Scripts**](./PCSMenu/src/Functions/Scripts)
        - [checkLinux.sh](./PCSMenu/src/Functions/Scripts/checkLinux.sh)
      - [**Tools**](./PCSMenu/src/Functions/Tools)
        - [**Run Script-Return Output**](./PCSMenu/src/Functions/Tools/Run%20Script-Return%20Output)
          - [executeCommand.sh](./PCSMenu/src/Functions/Tools/Run%20Script-Return%20Output/executeCommand.sh)
    - [PCSFunc.sh](./PCSMenu/src/PCSFunc.sh)
    - [main.rs](./PCSMenu/src/main.rs)
    - [menu.rs](./PCSMenu/src/menu.rs)
    - [utils.rs](./PCSMenu/src/utils.rs)
- [README.md](./README.md)
- [**Scripts**](./Scripts)
  - [**Vault**](./Scripts/Vault)
    - [auto-all-env.sh](./Scripts/Vault/auto-all-env.sh)
    - [go.mod](./Scripts/Vault/go.mod)
    - [go.sum](./Scripts/Vault/go.sum)
    - [main.go](./Scripts/Vault/main.go)
    - [**vaultCommon**](./Scripts/Vault/vaultCommon)
      - [vault_common.go](./Scripts/Vault/vaultCommon/vault_common.go)
    - [**vaultPull**](./Scripts/Vault/vaultPull)
      - [vault_pull_module.go](./Scripts/Vault/vaultPull/vault_pull_module.go)
    - [**vaultPush**](./Scripts/Vault/vaultPush)
      - [vault_push_module.go](./Scripts/Vault/vaultPush/vault_push_module.go)
- [bun.lockb](./bun.lockb)
- [commitlint.config.cjs](./commitlint.config.cjs)
- [package.json](./package.json)
- [renovate.json](./renovate.json)
- [repoTree.py](./repoTree.py)
