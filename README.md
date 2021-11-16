# fastapi-tutorial-cockroachdb-sync

The FastAPI SQL database tutorial modified to use CockroachDB.

Proof-of-concept that using FastAPI with CockroachDB does *not* require async.

See

https://fastapi.tiangolo.com/tutorial/

and

https://fastapi.tiangolo.com/tutorial/sql-databases/

for details on using the tutorial (installing FastAPI,
launching uvicorn, etc.).

GitHub discussion:

https://github.com/cockroachdb/sqlalchemy-cockroachdb/issues/165

Notes:

- You may need to tweak `SQLALCHEMY_DATABASE_URL` in database.py to connect
to your CockroachDB instance.

- This code includes a couple of minor updates for compatibility with
SQLAlchemy 1.4/2.0.
