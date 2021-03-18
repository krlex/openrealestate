#Open Real Estate in Vagrant box

this installed in box and you can use free version of Open Real estate platform
if you want to use pro version go to:

[OpenRealEstate](https://open-real-estate.info)

```
`sudo echo "192.168.33.10   www.example.com " >> /etc/hosts`
`vagrant init krlex/OpenRealEstate`
`vagrant up`
```
And than you go to your browser for example:

```
`www.example.com`
```
And you can see site
you must first register like me:
Database user name: `user`
Password for database user: `password`
Database server: `localhost`
Database port: `3306`
Database name: `openrealestatedb`
Prefix for tables: `ore_pa_`
Administrator email:` admin@example.com` # this you can use whatever you want
Administrator name: `admin` # this you can use whatever you want
Administrator password: `password` # this you can use whatever you want
And the other you can do your self and don't forget to mark:
` I accept the terms of the License agreement ` and
` I accept the terms of the Technical Support Terms `
and you install
