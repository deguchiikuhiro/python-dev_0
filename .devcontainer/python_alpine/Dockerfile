FROM python:3-alpine

RUN set -eux; \
	\
	apk add --no-cache --virtual .build-deps \
		gcc \
		python3-dev \
		musl-dev \
		linux-headers \
	; \
  pip install --upgrade pip \
  ; \
  pip install ipykernel jupyter ruff\
  ; \
  apk del --no-network .build-deps