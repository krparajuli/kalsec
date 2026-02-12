---
title: FAQ
---


# Image Repositories
1. How can I add docker login to a k8s cluster?
> Add a secret; Reference it on your deployment with `spec.imagePullSecrets.name` for deployment templates or pods. See Claude answer and instructions [here](https://claude.ai/share/a3aa6fa9-a85d-418f-85cf-9443cdd10df8)

