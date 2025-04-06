FROM node:18

WORKDIR /app

COPY . .

EXPOSE 3001

CMD [ "node", "index.js" ]


# docker run --rm -it -v $(pwd)/:/app -p 3000:3001 node:18 bash
# docker build -t node .        
# docker run --rm -d -p 3000:3001 node    