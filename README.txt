ShopNow - Minimal Bootstrap E-commerce Template
-----------------------------------------------
How to use:
1. Unzip and open index.html in browser, or serve with a local server:
   python3 -m http.server 8000
2. For Jenkins deployment:
   - Push this repo to GitHub
   - Create Jenkins job to pull repo and copy files to your webserver directory
   - Example deploy script:
     rm -rf /var/www/my-frontend/*
     cp -R * /var/www/my-frontend/
