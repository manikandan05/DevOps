## Create A Helm Chart

### Create a Helm Chart with the following command
```
helm create mychart
 ```

## Install Helm Chart

`cd` into the `mychart` directory.

Install the Helm Chart that's in your current directory and give it a name called `nginxapp`
```
helm install nginxapp .
```

## Upgrade A Chart

Go into the `values.yaml` file within the Helm Chart that you created and change the replica count to `2`. The replica count should be on line 5.

Run the Upgrade command
```
helm upgrade nginxapp .
```
## Uninstall The Helm Chart

Uninstall a Helm Chart with the following command
```
helm uninstall nginxapp
```