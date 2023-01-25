artifacts we use:
- ranger-plugins-cred-<version>.jar
- ranger-plugins-common-<version>.jar
- ranger-plugins-audit-<version>.jar
- ranger-<version>-admin.tar.gz

- rename all artifact versions to `<version>-vinted-<patch_number>` create tag release in github
- run build_ranger_using_docker.sh
- artifacts will be  from snapshot to `<version>-vinted-<patch_number>`
- extract `ranger-<version>-admin.tar.gz` tar and upload relevant jars to cloudsmith raw-hosted-oom repo
- upload `ranger-<version>-admin.tar.gz` to cloudsmith