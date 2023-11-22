# powerapi-env-starter

This kills the processes on 27017 and 8086 before starting the containers.

```
$ sudo chmod +x ./start_env.sh
$ ./start_env.sh
```


mongo_source 

```0.0.0.0:27017->27017/tcp, :::27017->27017/tcp   ```

influx_dest 

```0.0.0.0:8086->8086/tcp, :::8086->8086/tcp  ``` 

powerapi/hwpc-sensor

``` no port ```

powerapi/smartwatts-formula

``` no port ```



