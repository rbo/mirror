# README

```bash
# Pull secret:
touch config.json
export DOCKER_CONFIG=$(pwd)
./oc-mirror --config=./imageset-config.yaml \
    --skip-missing --continue-on-error \
    docker://mirror-registry.disco.coe.muc.redhat.com:8443
```

