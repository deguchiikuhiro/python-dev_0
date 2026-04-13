FROM ghcr.io/astral-sh/uv:alpine

WORKDIR /workspace
RUN set -eux; \
  uv python install 3.14 \
  ; \
  uv tool install ruff@0.15.10
