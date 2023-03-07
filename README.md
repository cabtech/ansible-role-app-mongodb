----
# ansible-role-app-mongodb

Installs [Mongodb](https://www.mongodb.com/)

[Ubuntu Instructions](https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-ubuntu)

## Default variables
| Name | Type | Value | Comment |
| ---- | ---- | ----- | ------- |
| mongodb_keyserver | URL | `hkp://keyserver.ubuntu.com` ||
| mongodb_pkg_dependencies | list(string) | see `defaults/main.yml` ||
| mongodb_pkg_name | string | mongodb-org | NOT mongodb (which is the Ubuntu maintained version) |
| mongodb_repo_path | APT source | see `defaults/main.yml` ||
| mongodb_repo_url | URL | `https://repo.mongodb.org/apt/ubuntu` ||
| mongodb_signing_url | URL | `https://www.mongodb.org/static/pgp/server-6.0.asc` ||
| mongodb_state | string | present | ... or absent |
| mongodb_svc_enabled | Boolean | true ||
| mongodb_svc_name | string | mongod ||
| mongodb_svc_state | string | started | Systemd status |

***
