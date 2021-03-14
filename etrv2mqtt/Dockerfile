FROM python:3.8
WORKDIR /app

RUN pip3 install 'git+https://github.com/mihtjel/etrv2mqtt.git@away_mode'

CMD [ "etrv2mqtt", "/data/options.json" ]
