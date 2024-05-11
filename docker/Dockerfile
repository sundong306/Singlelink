FROM node
RUN git clone https://github.com/sundong306/Singlelink.git
WORKDIR Singlelink
RUN npm i --ignore-scripts

COPY entrypoint.sh /entrypoint.sh

EXPOSE 3000

CMD ["/entrypoint.sh"]
