# NGINX

https://www.nginx.com/

# Starting and Stopping NGINX

Change to the bin directory after a successful build

``` ]# /nginx/sbin ```

Start the server in standalone mode

``` ./nginx ```

To stop the server

``` ./nginx -s stop ```

# default Package
* gcc
* pcre
* pcre-devel
* zilb
* zlib-devel
* gd
* gd-devel
* libxml2
* libxslt
* openssl
* openssl-devel

# NGINX Compile Options
`` ./configure --prefix=/nginx --with-http_ssl_module --with-http_realip_module --with-http_stub_status_module ``

# Default Module
* --without-http
	* port, location, error page등 웹서버 기본 설정 모듈
* --without-http_access_module
	* IP 주소에 기반한 Allow/Deny 접근 모듈
* --without-http_auth_basic_module
	* 기본 HTTP 인증 모듈
* --without-http_autoindex_module
	* 자동 색인(디렉토리, 파일 리스팅) 모듈
* --without-http_browser_module
	* 사용자 에이전트 문자열을 해석하는 브라우저 모듈
* --without-http_charset_module
	* 웹페이지를 재인코딩하는데 사용되는 캐릭터셋 모듈
* --without-http_empty_gif_module
	* 메모리로부터 1x1 GIF 이미지를 서비스하는 Empty GIF 모듈
* --without-http_fastcgi_module
	* FastCGI 프로세스와 연동되는 FastCGI 모듈
* --without-http_geo_module
	* IP 주소 범위에 따라 변수를 정의하는 GEO 모듈
* --without-http_gzip_module
	* gzip 압축 모듈
* --without-http-limit_req_module
	* 사용자등 요청 수를 제한하는 모듈
* --without-http_limit_zone_module
	* 정의된 지역에 따라 자원의 사용을 제한하는 Limit Zone 모듈
* --without-http_map_module
	* map 블록을 선언할 수 있는 모듈
* --without-http_memcached_module
	* 메모리 캐시 데몬과 연동되는 모듈
* --without-http_proxy_module
	* 요청을 받아 다른 서버로 전달하는 프록시 모듈
* --without-http_referrer_module
	* Referer 제어 모듈
* --without-http_rewrite_module
	* rewrite 모듈
* --without-http_scgi_module
	* SCGI 프로토콜 지원 모듈
* --without-http_split_client_module
	* 조건에 따라 클라이언트를 분할하는 모듈
* --without-http_ssi_module
	* 서버 측 SSI 모듈
* --with-http_upstream_ip_hash_module
	* 부하 균등 구조를 설정하는 모듈
* --without-http-userid_module
	* 쿠키를 통해 사용자 식별을 제공하는 사용자 ID 모듈
* --without-http_uwsgi_module
	* uWSGI 프로토콜 지원 모듈
	
# NGINX VERSION
nginx 1.21.1
