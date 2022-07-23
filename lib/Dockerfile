FROM quay.io/souravkl11/raganork:multidevice

RUN git clone https://github.com/criclife2/raganork-md
WORKDIR /skl/Raganork
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines
CMD ["node", "index.js"]
