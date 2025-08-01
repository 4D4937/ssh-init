# ssh-init

## Setup

Add these secrets to your repo:

* `SSH_HOST` – VPS IP/hostname
* `SSH_PASSWORD` – Root password
* `SSH_PUBLIC_KEY` – Your public key (`id_rsa.pub`)
* `SSH_PRIVATE_KEY` – Your private key (`id_rsa`)

## Run

Trigger **Init SSH Key and Test** in **Actions**.
It will:

1. Install `sshpass`
2. Copy your public key to the VPS
3. Configure SSH in the runner
4. Test the connection

Example output:

```
vps-host
root
Fri Aug  1 14:32:00 UTC 2025
```

---

If you want, I can make an **even shorter one-liner** README for GitHub’s main page.
Do you want me to do that?
