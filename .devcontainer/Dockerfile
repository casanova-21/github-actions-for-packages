FROM mcr.microsoft.com/vscode/devcontainers/universal:1-linux

RUN whoami
RUN grep codespace /etc/passwd
RUN pwd
RUN ls -ld
RUN wget -O ~/tf.zip https://releases.hashicorp.com/terraform/1.0.2/terraform_1.0.2_linux_amd64.zip
RUN unzip -d ~ ~/tf.zip
