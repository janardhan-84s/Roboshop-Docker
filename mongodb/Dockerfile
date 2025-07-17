
# from instruction takes the mongodb image from official docker hub 
FROM mongo:7.0 
# Copy inst copies the "master.data.js " file in the below location then docker automatical
# pick up and run the script.
# No need to copy the file in  catalogue component
## The "master-data.js " is default data for categories component.
COPY *.js /docker-entrypoint-initdb.d

