# ansible-influxevent

Installs influxevent (https://gitlab.com/devopsworks/tools/influxevent)

This role does not check if influxevent is already installed and overrides
existing binary (no way to check version in influxevent yet).

## Variables

- `influxevent_cronfiles`: array of files to populate (default: populate
  `ansible_user` cronfile)
- `influxevent_force_install`: forces installation of influxevent even if it is
  already installed
- `influxevent_skip_environment`: do not deploy environment vars in crontab (default: true)"
- `influxevent_influx_database`: influxdb database"
- `influxevent_influx_url`: influxdb URL"
- `influxevent_influx_username`: influxdb username"
- `influxevent_influx_password`: influxdb password"
- `influxevent_influx_tags`: influxdb tags"
  