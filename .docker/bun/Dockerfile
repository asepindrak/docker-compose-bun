# use the official Bun image
# see all versions at https://hub.docker.com/r/oven/bun/tags
FROM oven/bun

WORKDIR /.docker/bun

COPY src ./
RUN bun install
COPY . .

CMD [ "bun", "run", "dev" ]