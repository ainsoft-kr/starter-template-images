FROM ghcr.io/ainsoft-kr/docker-template-images/templates/base

ARG DEBIAN_FRONTEND=noninteractive

USER root

RUN apt-get update && apt-get install -y \
	elixir \
	erlang \
	&& rm -rf /var/lib/apt/lists/*

USER ainsoft