# Microbox Hosting Provider Integrations

## Official Integrations

### Amazon Web Services (AWS)
Microbox officially supports deploying apps to [Amazon Web Services (AWS)](https://aws.amazon.com/). You can select AWS as a provider in the Microbox Dashboard.

- **Adapter Repo**: https://github.com/mu-box/microbox-adapter-aws
- **Contributors**: [@jedgalbraith](https://github.com/jedgalbraith)

### DigitalOcean (DO)
Microbox officially supports deploying apps to [DigitalOcean](https://www.digitalocean.com/). You can select DO as a provider in the Microbox Dashboard.

- **Adapter Repo**: https://github.com/mu-box/microbox-adapter-digitalocean
- **Contributors**: [@tylerflint](https://github.com/tylerflint)

### Linode (LN)
Microbox officially supports deploying apps to [Linode](https://www.linode.com/). You can select LN as a provider in the Microbox Dashboard.

- **Adapter Repo**: https://github.com/mu-box/microbox-adapter-linode
- **Contributors**: [@jedgalbraith](https://github.com/jedgalbraith), [@lyondhill](https://github.com/lyondhill)

### Azure Resource Manager (AZR) _(Beta)_
Microbox is testing official support for deploying apps to [Azure Resource Manager](https://azure.microsoft.com/). You can select AZR as a provider in the Microbox Dashboard.

- **Adapter Repo**: https://github.com/mu-box/microbox-adapter-libcloud
- **Contributors**: [@danhunsaker](https://github.com/danhunsaker), [@jjkester](https://github.com/jjkester), [@tylerflint](https://github.com/tylerflint)

### Azure Classic (AZC) _(Beta)_
Microbox is testing official support for deploying apps to [Azure Classic](https://azure.microsoft.com/). You can select AZC as a provider in the Microbox Dashboard.

- **Adapter Repo**: https://github.com/mu-box/microbox-adapter-libcloud
- **Contributors**: [@danhunsaker](https://github.com/danhunsaker), [@jjkester](https://github.com/jjkester), [@tylerflint](https://github.com/tylerflint)

### Google Compute Engine (GCE) _(Beta)_
Microbox is testing official support for deploying apps to [Google Compute Engine](https://cloud.google.com/compute/). You can select GCE as a provider in the Microbox Dashboard.

- **Adapter Repo**: https://github.com/mu-box/microbox-adapter-libcloud
- **Contributors**: [@danhunsaker](https://github.com/danhunsaker), [@jjkester](https://github.com/jjkester), [@tylerflint](https://github.com/tylerflint)

### OVH _(Beta)_
Microbox is testing official support for deploying apps to [OVH](https://www.ovhcloud.com/). You can select OVH as a provider in the Microbox Dashboard.

- **Adapter Repo**: https://github.com/mu-box/microbox-adapter-libcloud
- **Contributors**: [@danhunsaker](https://github.com/danhunsaker), [@jjkester](https://github.com/jjkester), [@tylerflint](https://github.com/tylerflint)

### Equinix Metal (formerly Packet) (PKT) _(Beta)_
Microbox is testing official support for deploying apps to [Equinix Metal](https://deploy.equinix.com/). You can select PKT as a provider in the Microbox Dashboard.

- **Adapter Repo**: https://github.com/mu-box/microbox-adapter-libcloud
- **Contributors**: [@danhunsaker](https://github.com/danhunsaker), [@jjkester](https://github.com/jjkester), [@tylerflint](https://github.com/tylerflint)

### Scaleway (SW) _(Beta)_
Microbox is testing official support for deploying apps to [Scaleway](https://www.scaleway.com/). You can select SW as a provider in the Microbox Dashboard.

- **Adapter Repo**: https://github.com/mu-box/microbox-adapter-libcloud
- **Contributors**: [@danhunsaker](https://github.com/danhunsaker), [@jjkester](https://github.com/jjkester), [@tylerflint](https://github.com/tylerflint)

### Vultr (VTR) _(Beta)_
Microbox is testing official support for deploying apps to [Vultr](https://www.vultr.com/). You can select VTR as a provider in the Microbox Dashboard.

- **Adapter Repo**: https://github.com/mu-box/microbox-adapter-libcloud
- **Contributors**: [@danhunsaker](https://github.com/danhunsaker), [@jjkester](https://github.com/jjkester), [@tylerflint](https://github.com/tylerflint)


## Community Integrations

### Proxmox
[Proxmox](https://www.proxmox.com/en/) is an open source cloud solution that allows you to build and manage your own virtual cloud. Proxmox can be used as a custom provider in the Microbox dashboard.

- **Provider Endpoint**: https://adapter-proxmox.nanobox.app/api/v1/
- **Documentation**: https://adapter-proxmox.nanobox.app/
- **Adapter Repo**: https://github.com/danhunsaker/nanobox-adapter-proxmox
- **Contributors**: [@danhunsaker](https://github.com/danhunsaker)

### Single Server
In those cases where you have hosting with a provider that isn't listed here, but still want to deploy with Microbox, install this adapter on that server, following the instructions in the documentation, and then connect directly to it when adding it as your provider. Single Server can be used as a custom provider in the Microbox dashboard.

- **Provider Endpoint**: https://{your-server-ip}:8000/ _(this adapter is installed on the same server you plan to deploy to)_
- **Documentation**: https://github.com/torfs-ict/nanobox-adapter-single-server/blob/master/README.md
- **Adapter Repo**: https://github.com/torfs-ict/nanobox-adapter-single-server
- **Contributors**: [@torfs-ict](https://github.com/torfs-ict)

### Google Cloud _(In Progress)_
This integration is in the works but will allow Microbox users to deploy to [Google Cloud](https://cloud.google.com/).

- **Provider Endpoint**: *Coming*
- **Documentation**: *Coming*
- **Adapter Repo**: https://github.com/jeffgodwyll/nanobox-googlecloud-adapter
- **Contributors**: [@jeffgodwyll](https://github.com/jeffgodwyll)
