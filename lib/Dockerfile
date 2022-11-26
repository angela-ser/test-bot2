FROM quay.io/xelectra/xasena:latest
RUN git clone https://github.com/angela-ser/test-bot2 /root/X-Asena
WORKDIR /root/X-Asena
RUN yarn install --network-concurrency 1
CMD ["node", "bot.js"] 


