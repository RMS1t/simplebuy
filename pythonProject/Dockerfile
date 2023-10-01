FROM python

WORKDIR /simplebuy

ENV PYTHONDONTWRITEBYTECODE 1



RUN pip install --upgrade pip

COPY ./requirements.txt .

RUN pip install -r requirements.txt

COPY . /simplebuy

ENTRYPOINT ["/usr/src/simplebuy/entrypoint.sh"]