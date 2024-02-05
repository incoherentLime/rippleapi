# rippleapi
adds the number of kWh generted by graig fatha as a sensor on home assistant.

To install, make a directory for sensors add `sensor: !include_dir_merge_list sensor` to configuration.yaml

in secrets.yaml input `ripple_api_url: https://rippleenergy.com/rest/member_data/<apikey>`
Works in energy dashboard under grid return for me.
Will add more projects as they are commissoned. 
