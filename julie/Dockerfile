FROM fusuf/whatsasena:latest

RUN git clone https://github.com/ramshad21/SHA-MWOL /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/ramshad21/media

CMD ["node", "bot.js"]
