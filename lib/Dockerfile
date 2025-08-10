FROM quay.io/toxic_kichux/whatskrizai:latest
RUN apk update && \
apk add --no-cache git ffmpeg
WORKDIR /root/Xero-MD/
RUN yarn install --network-concurrency 1
CMD ["node", "index.js", "--max_old_space_size=2560"]
