FROM tensorflow/tensorflow:2.2.0
RUN mkdir -p /app
WORKDIR /app
COPY . /app
RUN python3 -m pip install -U pip
RUN pip3 install -r requirements.txt
RUN pip3 install -U spacy
# RUN python3 -m spacy download en
RUN pip3 install --user rasa
RUN pip3 install --user sanic==19.9.0