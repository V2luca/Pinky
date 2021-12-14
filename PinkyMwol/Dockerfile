FROM quay.io/lyfe00011/test:beta

RUN git clone  /rohttps://github.com/V2luca/Pinkyot/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/afnanplk/uploads
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
RUN npm install supervisor -g
CMD ["node", "bot.js"]
