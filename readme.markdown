# Minecraft PHP Query class

## Usage

### query

    MinecraftQuery::query($address, $port = 25566, $timeout = 2);

Queries a Minecraft server

**Parameters:**  
`$address` - IP address to the Minecraft server.
`$port` - Port of the Minecraft server.
`$timeout` - Time until giving up on connecting to the Minecraft server.

**Returns:**  
An array on success, FALSE on failure.

## License

Copyright (c) 2012 Scott Reed (h02), released under the GPL v3.