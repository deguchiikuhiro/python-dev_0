FROM ghcr.io/astral-sh/uv:bookworm-slim

RUN set -eux; \
  uv python install 3.13 \
  ; \
  uv init uv-project

WORKDIR uv-project