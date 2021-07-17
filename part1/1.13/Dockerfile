FROM golang:1.16
WORKDIR /usr/src/app
COPY example-backend .
EXPOSE 8080
RUN go build
CMD [ "./server" ]