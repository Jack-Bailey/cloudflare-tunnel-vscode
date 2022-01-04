<div align="center">
    <h1>Cloudflare Tunnel for VSCode</h1>
    <a href="https://marketplace.visualstudio.com/items?itemName=IvanArjona.cloudflaretunnel">
        <img src="images/icon.png" width="150px" alt="VSCode Marketplace badge" />
    </a>
    <br>
    <em>A Visual Studio code extension to crea a local tunnel so your local http server can be accessed remotely using <a href="https://www.cloudflare.com/es-es/products/tunnel/">Cloudflare Argo Tunnel</a></em>
</div>

<br>
<br>

# Commands

## Start a local tunnel

```
Cloudflare Tunnel: Start
```

## Stop your local tunnel

```
Cloudflare Tunnel: Stop
```

## Get the cloudflared version

```
Cloudflare Tunnel: Version
```

## Check if the tunnel is running

```
Cloudflare Tunnel: Is running?
```

## Get the current tunnel url

```
Cloudflare Tunnel: Get url
```


## Login with your cloudflare account

```
Cloudflare Tunnel: Login
```

## Logout from your cloudflare account

```
Cloudflare Tunnel: Logout
```

# Using your custom domain

First login to you cloudflare account using running the command `Cloudflare Tyunnel: Login`.

Go to your editor settings page file or edit your `settings.json`.

Set the setting `cloudflaretunnel.tunnel.hostname` to one subdomain not in use.
