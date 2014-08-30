How to make rpm
-----

```sh
yum install rpmdevtools
rpmdev-setuptree

QA_RPATHS=0x0002 rpmbuild -bb specs/ngx_openresty.spec
```
