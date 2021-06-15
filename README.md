compile command:

    ./configure --sbin-path=/usr/sbin --error-log-path=/var/log/nginx.err --pid-path=/var/run/nginx.pid --user=www-data --with-ld-opt="-Wl,-rpath,/usr/lib" --prefix=/etc/nginx --with-http_ssl_module --with-http_stub_status_module  --with-http_realip_module --with-http_gunzip_module --with-http_gzip_static_module --with-http_stub_status_module --add-module=/root/ngx_devel_kit  --add-module=/root/set-misc-nginx-module

    make -j2
    make install
