FROM jupyter/base-notebook:latest
  
WORKDIR /usr/src/app
      
# Setting ENV for docker jupyter notebook
ENV CHOWN_EXTRA="/usr/src/app"
ENV CHOWN_EXTRA_OPTS="-R" 
  
# Install pakages
RUN pip install --upgrade pip
COPY ./requirements.txt .
RUN pip install -r requirements.txt 
