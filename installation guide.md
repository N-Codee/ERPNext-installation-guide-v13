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

*Git is the most commonly used version control system. Git tracks the changes you make to files, so you have a record of what has been done, and you can revert to specific versions should you ever need to. Git also makes collaboration easier, allowing changes by multiple people to all be merged into one source.*

    sudo apt-get install git
    
### STEP 2 install python-dev

*python-dev is the package that contains the header files for the Python C API, which is used by lxml because it includes Python C extensions for high performance.*
    
    sudo apt-get install python3-dev
    
### STEP 3 Install setuptools and pip (Python's Package Manager)

*Setuptools is a collection of enhancements to the Python distutils that allow developers to more easily build and distribute Python packages, especially ones that have dependencies on other packages. Packages built and distributed using setuptools look to the user like ordinary Python packages based on the distutils.

pip is a package manager for Python. It's a tool that allows you to install and manage additional libraries and dependencies that are not distributed as part of the standard library.*

    sudo apt-get install python3-setuptools python3-pip
