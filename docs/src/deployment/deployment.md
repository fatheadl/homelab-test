# Deploy the homelab

> It will take a while to build the tools container and download Rocky Linux ISO on the first time

Open the tools container, which includes all the tools needed:

```sh
make tools
```

Build the lab:

```sh
make
```

Yes it's that simple! Check the status using the following command:

```sh
watch ./scripts/get-status
```

While waiting for all services to become healthy, continue to the next section to update your DNS.
