# homelab

GitOps state for the k3s homelab, synced by Argo CD.

**Rules (public repo):** no plaintext secrets — only `SealedSecret` manifests;
no server IPs or tailnet FQDNs, ever, including in commit messages. History is forever.
