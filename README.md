# pg_upgrade-docker
PostgreSQL database upgrade docker image


## Warning!

- This image will overwrite your `postgresql.conf`.

- Downgrade may be impossible! 
  E.q. you can't downgrade lower than PostgreSQL 10 because of pg_receivexlog becames pg_receivewal, pg_resetxlog becomes pg_resetwal, pg_xlogdump becomes pg_waldump & etc.
