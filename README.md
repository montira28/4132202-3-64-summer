version: '3'

services:
  web: 
    image: nginx
    ports:
      - "8000:80"