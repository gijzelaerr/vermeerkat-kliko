FROM kernsuite/base:1
RUN pip install kliko==0.8
RUN docker-apt-install python-katdal python-casacore
ADD kliko /
ADD kliko.yml /
ADD blank.ms /var/kat/static/blank.ms
