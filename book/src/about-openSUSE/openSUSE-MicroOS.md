# openSUSE MicroOS

<div style="display: flex; align-items: top;">
    <img
        style="width: 75%; float: left; padding-right: 1em;"
        src="assets/openSUSE-MicroOS-light-horizontal.svg"
        alt="openSUSE MicroOS Logo"
    />
    <div>

**openSUSE MicroOS** is a modern Linux operating system based on [openSUSE Tumbleweed](index.html#opensuse-tumbleweed) which also serves as base for [openSUSE Kubic](index.html#opensuse-kubic), a Container as a Service platform.
    </div>
</div>
<p style="clear: both; padding-top: 15px;" />

Few of the main **openSUSE MicroOS** characteristics are:
- **Small**: Lightweight images designed to be deployed for a specific use case
- **Scalable**: Optimized for large deployments while capable as a single machine OS
- **Always up-to-date**: Updates are automatically applied without impacting the running system
- **Resilient**: In case of trouble the system automatically rolls back to last working state
- **Fast**: Doesn't ship with baggage that slows it down

In other words **openSUSE MicroOS** is an operating system you don't have to worry about. It's designed for but not limited to container hosts and edge devices. Due to the focus on unattended operation it's especially suited for large deployments. openSUSE MicroOS inherits the openSUSE Tumbleweed and SUSE Linux Enterprise knowledge while redefining the operating system into a small, efficient and reliable distribution.

Major features of **openSUSE MicroOS** are:
- Read-only root filesystem to avoid accidental modifications of the OS
- The Transactional Updates technology leverages btrfs snapshots to apply package updates without interfering with the running system
- health-checker to verify the OS is operational after updates. Automatically rolls back in case of trouble.
- cloud-init for initial system configuration during first boot on Cloud (includes OpenStack)
- Combustion and Ignition for initial system configuration during first boot on all other images.
- Designed to fit perfectly into existing openSUSE or SUSE Linux Enterprise environments
- Podman Container Runtime available
- Rolling Release: Every new openSUSE Tumbleweed snapshot also automatically produces a new openSUSE MicroOS release. The Leap based version automatically updates when maintenance updates for Leap are published.

To learn more about **openSUSE MicroOS** system design, please see [relevant documentation from the openSUSE project](https://en.opensuse.org/Portal:MicroOS/Design).
