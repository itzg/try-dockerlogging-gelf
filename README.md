To try this out:

    docker-compose up -d

Look in the `logs-out` directory for the aggregate `all.log` and then the
host-container specific logs organized by directory per host.

In my case I saw the following files:

```
> find logs-out
logs-out
logs-out/all.log
logs-out/moby
logs-out/moby/trydockerlogginggelf_noise-date_1-2017.06.13.log
logs-out/moby/trydockerlogginggelf_noise-ping_1-2017.06.13.log
```
