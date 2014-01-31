
    mkdir nil/
    touch nil
    gcf push my-standalone-demo -i 1 -m 64M -b https://github.com/wwy/buildpack-bash

    curl http://my-standalone-demo.cfapps.io

