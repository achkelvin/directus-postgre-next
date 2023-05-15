FROM directus/directus:10.0.0

USER root
RUN corepack enable \
    && corepack prepare pnpm@8.3.1 --activate

USER node
RUN pnpm install moment uuid