# vpndetection
JavaScript library for vpndetection.net
# main
```js
async function main(){
    const {vpndetection} = require('./vpndetection');
    const vpn= new vpndetection();
    let req=await vpn.my_ip()
    console.log(req)
}
main()
```
