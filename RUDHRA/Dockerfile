FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Sameena00/Diyamwol /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/prince-rudh/media

CMD ["node", "bot.js"]
