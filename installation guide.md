# ERPNext-installation-Guide ubuntu 18, 20
## Pre-requisites

    Python 3.10+
    Node.js 14+
    Redis 5                                       (caching and real time updates)
    MariaDB 10.3.x / Postgres 9.5.x               (to run database driven apps)
    yarn 1.12+                                    (js dependency manager)
    pip 20+                                       (py dependency manager)
    wkhtmltopdf (version 0.12.5 with patched qt)  (for pdf generation)
    cron                                          (bench's scheduled jobs: automated certificate renewal, scheduled backups)
    NGINX                                         (proxying multitenant sites in production)

### STEP 1 Install git
