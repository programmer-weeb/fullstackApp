FROM node

WORKDIR /app

COPY package.json .

RUN npm install 

COPY . .

ENV MONGODB_URI=mongodb+srv://ahmed:ahmed@cluster0.7y3i8ap.mongodb.net/?retryWrites=true&w=majority

EXPOSE 4000

CMD ["npm", "start"]