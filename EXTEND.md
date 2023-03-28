# ENABLE OTP AUTO CHALLENGE FOR JumpServer

## HOW TO BUILD
```bash
# add cflags -D__HS_AUTO_OTP_CHALLENGE__=ON

./configure \
--with-cflags-after='-D__HS_AUTO_OTP_CHALLENGE__=ON'
```


## HOW TO USE
```bash
OTP_SECRET=${OTP_SECRET} ./ssh jms
```

