FROM cyclus/cyclus:latest

COPY . /cycamore
WORKDIR /cycamore
ENV PATH="/usr/bin:${PATH}"
RUN python install.py -j2 --build-type=Release --prefix /usr/
