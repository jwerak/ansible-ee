# Execution Environment for gcp

## Create image

Build image:

`ansible-builder build -v3 -t quay.io/jwerak/ansible-ee-gcp`

Push image to registry:

`podman push quay.io/jwerak/ansible-ee-gcp`
