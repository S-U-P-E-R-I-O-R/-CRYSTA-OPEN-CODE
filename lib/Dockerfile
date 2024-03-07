FROM quay.io/toxic_kichux/whatskrizai:latest
RUN git clone https://github.com/S-U-P-E-R-I-O-R/-CRYSTA-OPEN-CODE /root/-CRYSTA-OPEN-CODE
WORKDIR /root/-CRYSTA-OPEN-CODE/
RUN yarn install
CMD ["node", "index.js", "--max_old_space_size=2560"]
