# Conky - Core Commands

Launch Conky with defaults:

`conky`

Create a new default config:

`conky -C > ~/.conkyrc`

Launch Conky with alternate configuration:

`conky -c path/to/config_file`

Daemonize Conky:

`conky -d`

Conky desktop alignment:

`conky -a   top|bottom|middle|right

Kill Conky and reload config:

`killall -SIGUSR1 conky`
