# Merbridge

Use eBPF to speed up your Service Mesh like crossing an Einstein-Rosen Bridge.

## Usage

Run the following simple command to accelerate your Istio-managed cluster with eBPF:

```bash
kubectl apply -f https://raw.githubusercontent.com/merbridge/merbridge/main/deploy/all-in-one.yaml
```

> Note: currently only works on Linux kernel >= 5.15, run `uname -r` to check your kernel version before installing Merbridge.
