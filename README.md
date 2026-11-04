<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=2496ED&center=true&vCenter=true&width=520&lines=Hi%2C+I%27m+Timo+(aka+Frizzay);DevOps+by+day%2C+homelab+goblin+by+night;I+touch+computers;Building+platforms+since+2020;Computer+go+beep+boop;Wow+you+really+read+all+of+that%3F;I%27m+in+your+walls;Jk...;Unless..%3F;Nah+I%27m+just+messing+with+you" alt="Hi, I'm Timo (aka Frizzay)" />

</div>

```console
frizzay@homelab:~$ whoami
timo  # but the internet knows me as Frizzay

frizzay@homelab:~$ cat /etc/motd
I'm a platform engineering consultant (that means I get paid for talking).
Building highly available cloud native platforms is my passion.
Ever since I was a small child, I knew I wanted to increase shareholder value.
```

## 🧬 `kubectl get human frizzay -o yaml`

```yaml
apiVersion: humans/v1alpha1     # still in alpha, breaking changes expected
kind: PlatformEngineer
metadata:
  name: timo
  labels:
    alias: frizzay
    habitat: homelab
    club: hertha-bsc            # hahohe 💙🤍
spec:
  replicas: 1                   # horizontal scaling blocked on cloning tech
  languages: [german, english, yaml]
  favoriteTools: [ansible, docker, kubernetes]
  restartPolicy: OnTea
  livenessProbe:
    exec:
      command: ["cat", "/dev/tea"]
    periodSeconds: 3600
status:
  phase: Running
  conditions:
    - type: Ready
      status: "True"
      reason: CaffeineLevelsNominal
```

## 🐳 Projects

| Project | What it does |
| --- | --- |
| 🔄 [**dnf-auto-setup**](https://github.com/Frizzay/dnf-auto-setup) | Ansible role for hands-off Fedora updates with `dnf5 automatic`. A report lands in Discord after every run, so I find out about reboots before my users do. Comes with an interactive playbook, so you don't have to write any YAML. |
| ⚽ [**hertha-cal**](https://github.com/Frizzay/hertha-cal) | A subscribable ICS calendar with every Hertha BSC competitive match, with reminders 30 and 5 minutes before kickoff. |
| 🤖 **FrizzBot** | A private Discord bot for music, levels, polls and moderation. |
| 🏠 **The homelab** | It's never finished, and that's the fun part. |

## 🧰 Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=ansible" width="48" alt="Ansible" title="Ansible" />
  <img src="https://skillicons.dev/icons?i=terraform" width="48" alt="Terraform" title="Terraform" />
  <img src="https://skillicons.dev/icons?i=docker" width="48" alt="Docker" title="Docker" />
  <img src="https://skillicons.dev/icons?i=kubernetes" width="48" alt="Kubernetes" title="Kubernetes" />
  <img src="https://skillicons.dev/icons?i=openshift" width="48" alt="Red Hat OpenShift" title="Red Hat OpenShift" />
  <img src="https://skillicons.dev/icons?i=linux" width="48" alt="Linux" title="Linux" />
  <img src="https://skillicons.dev/icons?i=bash" width="48" alt="Bash" title="Bash" />
  <br />
  <img src="https://skillicons.dev/icons?i=githubactions" width="48" alt="GitHub Actions" title="GitHub Actions" />
  <img src="https://skillicons.dev/icons?i=gitlab" width="48" alt="GitLab" title="GitLab" />
  <img src="assets/forgejo.svg" width="48" alt="Forgejo" title="Forgejo" />
  <img src="assets/tekton.svg" width="48" alt="Tekton" title="Tekton" />
  <img src="https://skillicons.dev/icons?i=grafana" width="48" alt="Grafana" title="Grafana" />
  <img src="https://skillicons.dev/icons?i=prometheus" width="48" alt="Prometheus" title="Prometheus" />
  <img src="https://skillicons.dev/icons?i=py" width="48" alt="Python" title="Python" />
</p>

## 📟 Changelog of my life

```diff
+ automated: server updates, deployments, Discord notifications, my own laziness
+ containerized: pretty much everything that holds still long enough
- not yet automated: making tea (PRs welcome)
- known issue: "just a quick change" in the homelab takes the entire weekend
```

```console
frizzay@homelab:~$ exit
logout
Connection to frizzay closed. Thanks for stopping by! ✌️
```
