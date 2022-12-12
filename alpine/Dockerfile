FROM postgres:15-alpine
RUN apt-get update && \
  apt-get install -y --no-install-recommends \
  postgresql-$PG_MAJOR-pgaudit 
