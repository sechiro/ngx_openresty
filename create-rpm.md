How to make rpm
-----

```sh
yum install rpmdevtools
rpmdev-setuptree

A_RPATHS=0x0002 rpmbuild -bb specs/ngx_openresty.spec
```
