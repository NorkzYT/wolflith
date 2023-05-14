# Launchpad 📝⚙🚀

## Info

A selection of fast starts for various technologies, including docker, kubernetes, ansible, linux, windows, and more. Great for learning, automation, and home laboratories!

Don't forget to ⭐ this repo and fork it! 👆

Anything you want to add? Make a pull request.

Details are provided in each folder 📁

Check out the new implementation of [PCSMenu](/PCSMenu) - a remarkable Bash-based Application Deployment tool, redefining simplicity and efficiency in deploying your favorite self-hosted applications. With an interactive menu system, versatile command execution, and unmatched customization capabilities, PCSMenu transforms complex deployment tasks into a breeze. Dive into the future of hassle-free application deployment with PCSMenu today!

Note: Adding a bunch of things, repository is still a work in progress!

## Documentation and guides here 👉 [The documentation site](https://docs.pcscorp.dev/)

## Usage

Make sure you have make installed. If you don't, run `sudo apt install make` or `sudo yum install make` depending on your distro.

After pulling the repo to your Linux machine of choice, run `make help`.

This will show you the available commands.

Afterwards run `make setup` to install the required dependencies.

## Contributing
I value all kinds of contributions from the community, be it bug fixes, improvements, or new features. If you're interested in contributing, here are some guidelines to follow:

Fork the Repository: Start by forking this repository to your own GitHub account.

Clone the Repository: After forking, clone the repository to your local machine to work on it.
```bash
git clone https://github.com/NorkzYT/Launchpad.git
```

Create a New Branch: Always create a new branch for your changes. This keeps the work isolated and makes it easy to later merge your changes back into the main repository.
```bash
git checkout -b [branch-name]
```

Make Your Changes: Implement your changes in the new branch. Be sure to commit in logical chunks and provide clear and descriptive commit messages.

Push Your Changes: After making your changes, push them to your forked repository on GitHub.
```bash
git push origin [branch-name]
```
Create a Pull Request: Go to your forked repository on GitHub and click the "New Pull Request" button. Ensure you're comparing the branch on your fork to the master branch on the original repository.

Describe Your Changes: In the pull request description, explain your changes, why you made them, and any testing you did. The more information the better!

Wait for Review: Now your changes are ready for review! I will review your changes as soon as I can. If I have any questions or request changes, I will communicate through the pull request.

Remember, contributions are not just about code - any resources, documentation, or tools that help the community are valuable. Thank you for your contribution!

## Credits

Created by Norkz with 💛

► YouTube <https://www.youtube.com/c/Norkz>

► Twitch <https://www.twitch.tv/polymathnorkz>

► Twitter  <https://twitter.com/PolymathNorkz>

► Discord <https://discord.com/users/282100214024896522>

► GitHub <https://github.com/NorkzYT>

### Tree Generated by markdown-notes-tree
---
<!-- tree generated by markdown-notes-tree starts here -->

- [**Ansible**](Ansible)
    - [**adhoc**](Ansible/adhoc)
        - [adhoc commands](Ansible/adhoc/adhoc.md)
    - [**collections**](Ansible/collections)
    - [**inventory**](Ansible/inventory)
    - [**k3s**](Ansible/k3s)
    - [**playbooks**](Ansible/playbooks)
    - [**templates**](Ansible/templates)
- [**Docker**](Docker)
    - [**AMD64**](Docker/AMD64)
        - [**AppFlowy**](Docker/AMD64/appflowy)
        - [**Browserless**](Docker/AMD64/browserless)
        - [**Discord**](Docker/AMD64/discord)
        - [**Docker-OSX**](Docker/AMD64/docker-osx)
        - [**dupeguru**](Docker/AMD64/dupeguru)
        - [**GitLab Repo Sync (Mirror)**](Docker/AMD64/gitlab)
        - [**guacd**](Docker/AMD64/guacd)
        - [**krusader**](Docker/AMD64/krusader)
        - [**memcached**](Docker/AMD64/memcached)
        - [**meshcentral**](Docker/AMD64/meshcentral)
        - [**Postgresql**](Docker/AMD64/Postgresql)
        - [**putty**](Docker/AMD64/putty)
        - [**pwm**](Docker/AMD64/pwm)
        - [**WebNut**](Docker/AMD64/webnut)
    - [**ARM64**](Docker/ARM64)
        - [**GitLab Repo Sync (Mirror)**](Docker/ARM64/gitlab)
    - [**Both**](Docker/Both)
        - [**adminer**](Docker/Both/adminer)
        - [**guacamole**](Docker/Both/apacheguacamole)
        - [**authelia**](Docker/Both/authelia)
        - [**authentik**](Docker/Both/authentik)
        - [**Binfmt**](Docker/Both/Binfmt)
        - [**bookstack**](Docker/Both/bookstack)
        - [**cloudcmd**](Docker/Both/cloudcmd)
        - [**cloudflared**](Docker/Both/cloudflared)
            - [**data**](Docker/Both/cloudflared/data)
        - [**coder**](Docker/Both/coder)
        - [**CodeServer**](Docker/Both/codeserver)
        - [**cryptgeon**](Docker/Both/cryptgeon)
        - [**Dashy**](Docker/Both/Dashy)
        - [**dozzle**](Docker/Both/dozzle)
        - [**duplicati**](Docker/Both/duplicati)
        - [**endlessh**](Docker/Both/endlessh)
        - [**firefly-iii**](Docker/Both/firefly-iii)
        - [**flame**](Docker/Both/flame)
        - [**gitlab-runner**](Docker/Both/gitlabrunner)
        - [**gokapi**](Docker/Both/gokapi)
        - [**homechart**](Docker/Both/homechart)
        - [**influxdb**](Docker/Both/influxdb)
        - [**littlelink-server**](Docker/Both/littlelinkserver)
        - [**mariadb**](Docker/Both/mariadb)
        - [**n8n**](Docker/Both/n8n)
        - [**ntp**](Docker/Both/ntp)
        - [**organizrv2**](Docker/Both/organizrv2)
        - [**ouroboros**](Docker/Both/ouroboros)
        - [**passwdpusher**](Docker/Both/passwdpusher)
        - [**portainer**](Docker/Both/portainer)
        - [**postgresql**](Docker/Both/postgresql)
        - [**proxy.py**](Docker/Both/proxy.py)
        - [**pterodactyl-panel**](Docker/Both/pterodactyl-panel)
        - [**pterodactyl-wings**](Docker/Both/pterodactyl-wings)
        - [**redis**](Docker/Both/redis)
        - [**speedtest**](Docker/Both/speedtest)
        - [**Squid**](Docker/Both/squid)
        - [**Syncthing**](Docker/Both/syncthing)
        - [**tailscale**](Docker/Both/tailscale)
        - [**tdarr**](Docker/Both/tdarr)
        - [**Traefik**](Docker/Both/Traefik)
        - [**Ubuntu-Desktop**](Docker/Both/ubuntu-desktop)
        - [**uptimekuma**](Docker/Both/uptimekuma)
        - [**Vault**](Docker/Both/vault)
            - [**static-appdata**](Docker/Both/vault/static-appdata)
                - [**config**](Docker/Both/vault/static-appdata/config)
        - [**vscode**](Docker/Both/vscode)
        - [**vwarden**](Docker/Both/vwarden)
        - [**watchtower**](Docker/Both/watchtower)
        - [**webtop**](Docker/Both/webtop)
        - [**WGEasy**](Docker/Both/wgeasy)
        - [**wikijs**](Docker/Both/wikijs)
        - [**wireguard**](Docker/Both/wireguard)
    - [**Static**](Docker/Static)
        - [**AppData**](Docker/Static/AppData)
            - [**Traefik**](Docker/Static/AppData/Traefik)
- [**Documentation**](Documentation)
    - [**Linux**](Documentation/Linux)
        - [**Shells**](Documentation/Linux/Shells)
            - [**INSTALL ZSH SHELL IN WSL / WSL2**](Documentation/Linux/Shells/Powerlevel10k.md)
            - [Shell info](Documentation/Linux/Shells/ShellInfo.md)
        - [**To create a new user account named username using the adduser command you would run:**](Documentation/Linux/adduser.md)
        - [Auto Execute Commands/Scripts During Reboot or Startup](Documentation/Linux/H-W-T-StartupScript.md)
        - [Chmod](Documentation/Linux/permissions.md)
    - [How to get more FreeForever Oracle Cloud Accounts](Documentation/FreeForeverOracle.md)
- [**K8s**](K8s)
    - [**cloudflare**](K8s/cloudflare)
    - [**gitlab runner**](K8s/gitlab-runner)
    - [**kube-prometheus-stack**](K8s/kube-prometheus-stack)
    - [**nextcloud**](K8s/nextcloud)
    - [**pterodactyl**](K8s/pterodactyl)
        - [**panel**](K8s/pterodactyl/panel)
            - [**node**](K8s/pterodactyl/panel/node)
    - [**traefik cert-manager let's encrypt**](K8s/traefik-cert-manager)
        - [**cert-manager**](K8s/traefik-cert-manager/cert-manager)
            - [**certificates**](K8s/traefik-cert-manager/cert-manager/certificates)
                - [**production**](K8s/traefik-cert-manager/cert-manager/certificates/production)
                - [**staging**](K8s/traefik-cert-manager/cert-manager/certificates/staging)
            - [**issuers**](K8s/traefik-cert-manager/cert-manager/issuers)
        - [**nginx**](K8s/traefik-cert-manager/nginx)
        - [**traefik**](K8s/traefik-cert-manager/traefik)
            - [**dashboard**](K8s/traefik-cert-manager/traefik/dashboard)
    - [**traefik + kubernetes**](K8s/traefik2-k3s-rancher)
        - [**config**](K8s/traefik2-k3s-rancher/config)
        - [**config-ingress-route**](K8s/traefik2-k3s-rancher/config-ingress-route)
            - [**kubernetes**](K8s/traefik2-k3s-rancher/config-ingress-route/kubernetes)
    - [**Uptime Kuma**](K8s/uptime-kuma)
- [**PCSMenu**](PCSMenu)
    - [**Auto**](PCSMenu/Auto)
    - [**Functions**](PCSMenu/Functions)
- [**Scripts**](Scripts)
    - [**Ansible**](Scripts/Ansible)
        - [**AlreadySetup**](Scripts/Ansible/AlreadySetup)
        - [**FirstTimeSetup**](Scripts/Ansible/FirstTimeSetup)
    - [**DoNotTouch**](Scripts/DoNotTouch)

<!-- tree generated by markdown-notes-tree ends here -->
---