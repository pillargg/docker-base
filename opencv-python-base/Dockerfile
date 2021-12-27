FROM python:3.9-bullseye

ENV TZ="America/New_York"
ARG DEBIAN_FRONTEND=noninteractive

ADD ["https://github.com/aws/aws-lambda-runtime-interface-emulator/releases/latest/download/aws-lambda-rie", "/usr/bin/aws-lambda-rie"]
RUN chmod +x /usr/bin/aws-lambda-rie

RUN pip3 install --no-cache-dir awslambdaric opencv-python
