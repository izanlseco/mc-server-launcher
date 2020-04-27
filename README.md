# What is this?
The idea was to make a simple launcher with some parameters to launch a minecraft server with forge installed.

The project works with forge version **forge-1.15.2-31.1.46.jar**

## Configuration
The following variables have to be defined before using the script:
```Groovy
def initialMemory = '-Xms2048M'
def maximumMemory = '-Xmx8192M'
def forgeVersion = 'forge-1.15.2-31.1.46.jar'
```
The following tests should be changed as the mentioned variables change:
```Groovy
assert initialMemory == '-Xms2048M'
assert maximumMemory == '-Xmx8192M'
assert forgeVersion == 'forge-1.15.2-31.1.46.jar'
```
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
## License
[MIT](https://choosealicense.com/licenses/mit/)
