
Install Ubuntu server 64 for Raspberry Pi



# OpenVPN workaround
`docker network create localdev --subnet 10.0.1.0/24`

And add

```
networks:
  default:
    external:
      name: localdev
```      


https://stackoverflow.com/questions/45692255/how-make-openvpn-work-with-docker