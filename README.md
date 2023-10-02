<h1 align="center">WhatsApp-API</h1>

> Servidor de WhatsApp para envío de mensajes desde la web.

## Install
```sh
npm install
```
## Config
```sh
cp .env-example .env

# Edit environment variables
APP_NAME="WhatsApp API"
APP_ENV="dev" # prod for production environment
APP_DOMAIN=example.com # your domain without http or https (example.com)
APP_PORT=3000 # your port
```

## Start
```sh
npm start
```

## Routes
<table>
    <tr>
        <th>TYPE</th>
        <th>ROUTE</th>
        <th>PARAMS</th>
        <th>RETURN</th>
    </tr>
    <tr>
        <td>GET</td>
        <td>/</td>
        <td></td>
        <td>OBJECT</td>
    </tr>
    <tr>
        <td>GET</td>
        <td>/status</td>
        <td></td>
        <td>OBJECT</td>
    </tr>
    <tr>
        <td>GET</td>
        <td>/login</td>
        <td></td>
        <td>OBJECT</td>
    </tr>
    <tr>
        <td>GET</td>
        <td>/logout</td>
        <td></td>
        <td>OBJECT</td>
    </tr>
    <tr>
        <td>GET</td>
        <td>/test</td>
        <td></td>
        <td>OBJECT</td>
    </tr>
    <tr>
        <td>POST</td>
        <td>/send</td>
        <td>{phone: "59175199157", text: "Hello", image_url: "https://my_image_url"}</td>
        <td>OBJECT</td>
    </tr>
</table>

## Credits
<a href="https://twitter.com/AgustinMejiaM" target="_blank">@AgustinMejiaM</a>  -   Developer