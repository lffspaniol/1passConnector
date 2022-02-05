# 1passConnector

### simple openvpn connector

- Install on pass cli [download](https://1password.com/pt/downloads/command-line/)

- Install [jq](https://stedolan.github.io/jq/)

  ```sh
  apt-get install jq
  ```

- Install openvpn
  ```sh
  apt-get install openvpn
  ```

### usage

make the signin in 1pass

```sh
    op signing "your domain" "your email"
```

```sh
    sh vpn "1pass iten" "path/to/openvpn/config"
```

### based on

[1pass-vpn](https://github.com/dgethings/1p-vpn)
