# Changelog

## 1.8.27-r1 (XXXX/XX/XX)

* Add `SMTP_ALLOW_FROM_OVERRIDE` env var

## 1.8.26-r0 (2024/05/01)

* msmtp 1.8.26 (#73)
* Alpine Linux 3.19 (#74)

## 1.8.25-r0 (2023/11/26)

* msmtp 1.8.25 (#69)
* Alpine Linux 3.18 (#69)

## 1.8.23-r0 (2023/05/02)

* msmtp 1.8.23 (#56)
* Alpine Linux 3.17 (#54)

## 1.8.22-r0 (2022/08/13)

* msmtp 1.8.22 (#51)
* Alpine Linux 3.16 (#50)

## 1.8.20-r0 (2022/03/26)

* msmtp 1.8.20

## 1.8.19-r2 (2022/03/13)

* Fix sysconfdir (#43)

## 1.8.19-r1 (2022/02/27)

* Add `SMTP_DSN_NOTIFY` and `SMTP_DSN_RETURN` env vars (#39)
* Alpine Linux 3.15 (#37)
* Native cross compilation (#34)

## 1.8.19-r0 (2021/11/15)

* msmtp 1.8.19

## 1.8.18-r0 (2021/10/27)

* msmtp 1.8.18

## 1.8.16-r0 (2021/09/17)

* msmtp 1.8.16

## 1.8.15-r3 (2021/08/15)

* alpine-s6 3.14-2.2.0.3 (#32)

## 1.8.15-r2 (2021/04/20)

* alpine-s6 3.13-2.2.0.3
* Add `SMTP_SET_FROM_HEADER` env var (#23)
* Add `SMTP_SET_DATE_HEADER` env var
* Add `SMTP_REMOVE_BCC_HEADERS` env var
* Add `SMTP_UNDISCLOSED_RECIPIENTS` env var

## 1.8.15-r1 (2021/03/18)

* Upstream Alpine update

## 1.8.15-r0 (2021/03/13)

* msmtp 1.8.15
* Switch to buildx bake

## 1.8.14-RC1 (2020/12/25)

* msmtp 1.8.14
* Do not fail on permission issue (#21)

## 1.8.11-RC1 (2020/08/07)

* msmtp 1.8.11
* Now based on [Alpine Linux 3.12 with s6 overlay](https://github.com/crazy-max/docker-alpine-s6/)

## 1.8.10-RC3 (2020/05/22)

* Set `S6_BEHAVIOUR_IF_STAGE2_FAILS` behavior

## 1.8.10-RC2 (2020/05/18)

* Fix `SMTP_DOMAIN` impl

## 1.8.10-RC1 (2020/05/18)

* Initial version based on [msmtp](https://marlam.de/msmtp/) 1.8.10
