# packer-CentOS8

```cmd
cd c:\packer-CentOS8
packer build centos8.json
```

- ./http/ks.cfg

Set the `keyboard` parameter as desired, for example: `keyboard --vckeymap=fr --xlayouts='fr'`

## Default credentials

The default credentials for this VM image are:

|Username|Password|
|--------|--------|
|packer|packer|
|root|packer|
