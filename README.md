<!-- TODO: add octoblu init scripts -->

# Meshblu Johnny-Five Raspberry Pi
This example provides an easy way to connect your Raspberry Pi to Meshblu with minimal configuration.

## What you'll need
1. Raspberry Pi w/ an Internet connection (via WiFi or ethernet)
1. A servo motor
1. An [Octoblu Accout](https://app.octoblu.com)

## Installation

<!-- TODO: Describe the installation process -->
1. Boot up your Raspberry Pi.
2. Connect your Pi to the internet
3. Install Node JS
```
wget http://node-arm.herokuapp.com/node_archive_armhf.deb && \
sudo dpkg -i node_archive_armhf.deb 
```
4. Go to your home directory.
5. "git clone https://github.com/octoblu/meshblu-johnny-five-rpi"
6. cd meshblu-johnny-five-rpi
7. Type "npm install"
8. Type "node index.js"
9. Use the UUID/TOKEN it generates and saves to meshblu.json to claim the device in app.octoblu.com
10. You can make the script run on boot using the example in /scripts. 
11. You can now use the device in your Octoblu design when the script is running.



## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
