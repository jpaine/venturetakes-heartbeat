# venturetakes-heartbeat

Free GitHub Actions timer that calls Venturetakes' public `POST /api/ingest/run-if-stale` every 15 minutes. The server decides whether to ingest (stale > 6h, min 6h between runs, one run at a time). No secrets.
