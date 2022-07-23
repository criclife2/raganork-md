FROM quay.io/souravkl11/raganork:multidevice

RUN git clone https://github.com/criclife2/raganork-md
WORKDIR /skl/Raganork
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN npm install
CMD ["node", "index.js"]
