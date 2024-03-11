FROM quay.io/loki-xer/jarvis-md:latest
RUN git clone https://github.com/Munaxxx/EZRA-XD /root/Munaxxx/
WORKDIR /root/Munaxxx/
RUN yarn install --network-concurrency 1
CMD ["npm", "start"]
