FROM postgres:15-alpine
RUN apk update && \
  apk install -y --no-install-recommends \
  postgresql-$PG_MAJOR-pgaudit 
