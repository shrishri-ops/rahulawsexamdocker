#install node
FROM node
#create Directory 
WORKDIR /app
#copy all files from laptop (dev)to container (/app)
COPY . .
#install node libraries inside container
RUN npm install 
#expose open the port 
EXPOSE 3000
#final cammand for exicute application 
CMD ["npm","start"]