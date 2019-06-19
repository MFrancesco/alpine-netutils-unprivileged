## Alpine netutils unprivileged

Alpine image with some net utils installed and a volume mount point under /mnt/volume that does not require to run as root.

Just `oc/kubectl run netutils --image=frehub/alpine-netutils-unprivileged --restart=Never --command -- /bin/bash -c 'while true; do sleep 1; done'
`




