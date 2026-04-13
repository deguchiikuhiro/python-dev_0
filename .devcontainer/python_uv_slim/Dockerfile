FROM ghcr.io/astral-sh/uv:trixie-slim

WORKDIR /workspace
RUN set -eux; \
  uv python install 3.14 \
  ; \
  uv tool install ruff@0.15.10
