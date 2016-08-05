# Docker

The docker role instals the latest version of docker.
No extra configuration is required, but there are some details you can change:

## Optional variables:

* docker_repo - link to the apt repository to install from
* docker_repo_key: - Apt repository key
* docker_repo_keyserver: The repository keyserver.
* docker_config_line: Additional options to pass to the docker daemon at start.
* docker_options: Additional options to pass to the docker daemon at start.
* docker_tls: Whether to use tls with docker cli
* docker_sysctl_path: path to the sysdtemd docker controll file
