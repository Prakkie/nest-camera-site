# nest-camera-site
Capture images from a nest camera and host in a local server

## Configuration
`issueToken`, `cookie` and `apikey` can be obtain by following the following instruction:
https://github.com/chrisjshull/homebridge-nest#using-a-google-account

`uuid` is the camera uuid you would like to capture. Similar to the instruction linked above, expect that you need to `Filter` for `get_image`. The string after `uuid=` and before `&` is your camera uuid.

These four items needs to be put into config.json
