
#  Static website for s2i deployment. 

#### Usage

This site can be deployed in conjunciton with https://github.com/flannon/s2i-nginx like this,

   oc new-app https://github.com/flannon/s2i-nginx~httpd://flannon/static-site --name my-static-site
