#workedddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd
FROM amancevice/superset
USER root
RUN apt-get install -y libaio1
RUN pip install cx_oracle==7.3.0
USER superset
