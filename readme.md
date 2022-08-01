# laboratory

laboratory is the next generation [Minecraft](https://minecraft.net) server management tool fully written in [Kotlin](https://kotlinlang.org)

### Installation

**Linux:**

1. Clone this repository using `git clone https://github.com/mooziii/laboratory.git`
2. cd into the folder using `cd laboratory`
3. Build a distribution using `gradlew distZip` 
4. Copy the zip file into the packages folder `cp build/distributions/laboratory-jvm.zip packages/laboratory-jvm.zip`
5. cd into the packages directory using `cd packages`
6. Run the installation script with root privileges: `sudo ./install.sh`
7. Complete installation by running `laboratory`

**Windows:**
Don't use this on Windows

**macOS:**
It may work, idk just why would you run a minecraft server on macOS

### Updating 

To update laboratory, just run the installation script again and confirm the copy action with `A`

### Usage

To create a server run `laboratory create <server-name> <server-software>`

To start an existing server run `laboratory start [server-name]` and select the server.

## Notes

laboratory currently supports [PaperMC](https://papermc.io), [QuiltMC](https://quiltmc.org), [Waterfall](https://papermc.io/downloads#Waterfall), [Velocity](https://papermc.io/downloads#Velocity) and [Vanilla](https://minecraft.net).
Support for other servers like [SpongeVanilla](https://spongepowered.org/downloads/spongevanilla) is planned.

This project was inspired by [pacmc](https://github.com/jakobkmar/pacmc) and [CloudNet](https://github.com/CloudNetService/CloudNet-v3)
