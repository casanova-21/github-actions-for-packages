FROM mcr.microsoft.com/vscode/devcontainers/universal:1-linux

RUN whoami
RUN grep codespace /etc/passwd
RUN pwd
RUN ls -ld
RUN sudo curl -o /usr/local/bin/tf.zip https://releases.hashicorp.com/terraform/1.0.2/terraform_1.0.2_linux_amd64.zip
RUN sudo unzip -d /usr/local/bin /usr/local/bin/tf.zip
