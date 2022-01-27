## ENABLE OTP AUTO CHALLENGE FOR JumpServer
```bash
# add cflags -D__HS_AUTO_OTP_CHALLENGE__=ON

./configure \
--with-cflags-after='-D__HS_AUTO_OTP_CHALLENGE__=ON'
```

