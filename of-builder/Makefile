OF_BUILDER_TAG?=latest
SQUASH?=true

build:
	docker build --build-arg http_proxy="${http_proxy}" --build-arg https_proxy="${https_proxy}" -t openfaas/of-builder:$(OF_BUILDER_TAG) . --squash=${SQUASH}

push:
	docker push openfaas/of-builder:$(OF_BUILDER_TAG)
