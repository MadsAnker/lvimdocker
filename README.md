# Docker compose for running Lunar Vim
I made this to run LunarVim consitently across platforms without having to worry about dependencies.
For now, it just persists the config in a docker volume. I will probably change this to allow for mounting of a config from the host.

## Running
```
docker compose run lvim
```
