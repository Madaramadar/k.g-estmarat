FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/Madaramadar/elsa /root/Madaramadar
WORKDIR /root/Madaramadar/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
