FROM quay.io/maherzubair/sigma-md:beta
RUN git clone https://github.com/j98fn4mf9/bot /root/j98fn4mf9/bot
WORKDIR /root/j98fn4mf9/bot
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
