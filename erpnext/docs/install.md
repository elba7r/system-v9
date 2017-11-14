# Install

<!-- title: Revalue ERP Installation -->

# Installation

Revalue ERP is based on the <a href="http://revaluesoft.com">Revalue Framework</a>, a full stack web framework based on Python, MariaDB, Redis, Node.

To intall Revalue ERP, you will have to install the <a href="https://github.com/elba7r/platform-v9">Revalue Bench</a>, the command-line, package manager and site manager for Revalue Framework. For more details, read the Bench README.

After you have installed Revalue Bench, go to you bench folder, which is     `revalue.bench` by default and setup **erp**.

    bench get-app erp {{ source_link }}

Then create a new site to install the app.

    bench new-site mysite

This will create a new folder in your `/sites` directory and create a new database for this site.

Next, install Revalue ERP in this site

    bench --site mysite install-app erp

To run this locally, run

    bench start

Fire up your browser and go to http://localhost:8000 and you should see the login screen. Login as **Administrator** and **admin** (or the password you set at the time of `new-site`) and you are set.

<!-- jinja -->
<!-- autodoc -->