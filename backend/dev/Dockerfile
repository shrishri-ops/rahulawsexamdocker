#install python
FROM python 
#create Directory 
WORKDIR /app
#copy all files from laptop (dev)to container (/app)
COPY . .
#install python libraries inside container
RUN pip install -r requirements.txt
#expose open the port 
EXPOSE 3001
#final cammand for exicute application 
CMD ["python","app.py"]