FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Darkside88hacker/mimo /Darkside/Mimo

WORKDIR /Darkside/mimo

ENV TZ=Africa/Harare

RUN npm install

RUN npm install supervisor -g
RUN yarn install --ignore-engines
CMD ["node", "index.js"]
