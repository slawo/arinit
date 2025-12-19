FROM mcr.microsoft.com/devcontainers/base:trixie

ENV DEBIAN_FRONTEND=noninteractive \
	LANG=C.UTF-8 \
	LC_ALL=C.UTF-8

RUN apt update && apt upgrade -y && \
	apt install -y --no-install-recommends \
	ca-certificates \
	curl \
	gnupg \
	jq \
	lsb-release \
	sudo \
	git \
	pip \
	ssh-client \
	sshpass \
	unzip \
	vim \
	wget \
	yq \
	zsh \
	&& rm -rf /var/lib/apt/lists/*

RUN apt update && apt upgrade -y && \
	apt install -y --no-install-recommends \
	ansible \
	ansible-lint \
	python3 \
	python3-pexpect \
	&& rm -rf /var/lib/apt/lists/*