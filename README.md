# multi-docker
This is a full nodejs sample project with multiple containers strategy.
The application hosts a fibonacci calculator built in React and it stores all values into the postgres database.

# Requirements
* Rancher Desktop container management tool

# How to use
On Rancher Desktop, you can either select `containerd - nerdctl` or `moby - dockerd` container runtime.

### `dockerd` container runtime
* Run `docker-compose build`
* Run `docker-compose up`

### `containerd` container runtime
* Run `nerdctl compose build`
* Run `nerdctl compose up`

### Access the application throught
* http://localhost:6050

### Stop all existing running containers
* Run `docker-compose down` or
* Run `nerdctl compose down`
