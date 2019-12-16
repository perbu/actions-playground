FROM python:3.8-alpine


RUN mkdir -p /opt

COPY echo.py /opt
COPY requirements.txt /opt

WORKDIR /opt
RUN pip install --no-cache-dir -r requirements.txt
CMD ["/opt/echo.py"]
