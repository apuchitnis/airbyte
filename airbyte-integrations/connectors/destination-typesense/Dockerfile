FROM airbyte/destination-typesense:latest

USER root
COPY . .
RUN pip install --no-cache-dir --no-deps --break-system-packages .
USER airbyte
