FROM quay.io/hermit/hermit-ser:latest

RUN git clone https://github.com/umar404/Umar-md /root/Umar-md
WORKDIR /root/Umar-md/
RUN yarn install --network-concurrency 1
CMD ["node", "index.js", "--max_old_space_size=2560"]
