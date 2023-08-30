FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/vajirarathnayaka/QUEEN-VARSHA /root/vajirarathnayaka
WORKDIR /root/vajirarathnayaka/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
