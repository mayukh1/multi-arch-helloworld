# multi-arch-helloworld
multi-arch-helloworld(java,go)

docker login -u <user> -p <pwd>

docker buildx ls

docker buildx create --name mybuilder --driver docker-container --bootstrap

docker buildx use mybuilder

docker buildx inspect --bootstrap

yum install qemu-kvm/sudo apt-get install qemu

docker buildx build --platform linux/amd64,linux/arm64,linux/arm/v7,linux/s390x,linux/ppc64le -t <username>/<image>:latest --push .
