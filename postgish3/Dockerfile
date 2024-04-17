FROM postgres:14

# Install PostGIS extension
RUN apt-get update && apt-get install -y \
    postgresql-14-postgis-3 \
    postgresql-14-postgis-3-scripts

# Install h3-pg extension
RUN apt-get install -y postgresql-14-h3