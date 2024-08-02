# Warren - Docker Containers :whale2:

This action takes a `docker compose` file and start all services declared in detached mode. Then it will wait for 10 seconds for the containers to start.

## Inputs

### `docker-compose-file`

**Required**: The docker-compose file path (absolute, relative or pattern paths are acceptable)

## Usage

```yml
- name: Warren - Docker Containers
  uses: warrenbrasil/docker-containers@v4
  with:
    docker-compose-file: ./docker-compose.yml
```
