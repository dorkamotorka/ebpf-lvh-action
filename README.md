# eBPF Kernel Compatibility Testing

Ensure your eBPF program runs on every supported Linux kernel—automate kernel testing with GitHub Actions and Little VM Helper (LVH).

## Features

* **Automated VM spin-up** for multiple kernel versions
* **CI/CD integration** via GitHub Actions
* **Lightweight VMs** managed by LVH (from Cilium)

## Available LVH Images

* `base`: minimal core utilities
* `kind`: extra containerd, Kubernetes, networking tools
* `complexity-test`: full build toolchain, tracing, BPF debugging
