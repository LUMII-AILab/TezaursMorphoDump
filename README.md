# Tezaurs Morphology Dump

Script to prepare an offline morphological data dump out of the Tezaurs.lv database to be used with https://github.com/LUMII-AILab/Morphology/ toolkit

Requires `psycopg`, which may require that PostgreSQL is installed. Fow Windows, PostgreSQL command line tools must be installed and Postgres/SQL/_version_/bin must be in path.

## Running

First, ceate `db_config.py` by copying `db_config_sample.py` and adjusting your DB connection credentials.

Then, for Latvian `python -m tezaurs_dump` or `python -m tezaurs_dump Latvian`.

For Latgalian `python -m tezaurs_dump Latgalian`


____________

P.S. Since 2026-04 development of this tool has been continued here.
