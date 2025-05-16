FROM postgres:17.2-alpine

# Copies the SQL files into the directory where PostgreSQL looks for initialization scripts.
COPY CreateScheme.sql InsertData.sql /docker-entrypoint-initdb.d/