FROM airbyte/destination-typesense:latest

ENV HOME=/tmp
COPY . ./airbyte/integration_code
RUN pip install --no-cache-dir ./airbyte/integration_code
