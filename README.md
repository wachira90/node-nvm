# node-nvm
node-nvm

C:\Users\admin>nvm

Running version 1.1.7.

Usage:

  nvm arch                     : Show if node is running in 32 or 64 bit mode.
  
  nvm install <version> [arch] : The version can be a node.js version or "latest" for the latest stable version.
                                 Optionally specify whether to install the 32 or 64 bit version (defaults to system arch).
                                 Set [arch] to "all" to install 32 AND 64 bit versions.
                                 Add --insecure to the end of this command to bypass SSL validation of the remote download server.
  
  nvm list [available]         : List the node.js installations. Type "available" at the end to see what can be installed. Aliased as ls.
  
  nvm on                       : Enable node.js version management.
  
  nvm off                      : Disable node.js version management.
  
  nvm proxy [url]              : Set a proxy to use for downloads. Leave [url] blank to see the current proxy.
                                 Set [url] to "none" to remove the proxy.
                                 
  nvm node_mirror [url]        : Set the node mirror. Defaults to https://nodejs.org/dist/. Leave [url] blank to use default url.
  
  nvm npm_mirror [url]         : Set the npm mirror. Defaults to https://github.com/npm/cli/archive/. Leave [url] blank to default url.
  
  nvm uninstall <version>      : The version must be a specific version.
  
  nvm use [version] [arch]     : Switch to use the specified version. Optionally specify 32/64bit architecture.
                                 nvm use <arch> will continue using the selected version, but switch to 32/64 bit mode.
  
  nvm root [path]              : Set the directory where nvm should store different versions of node.js.
                                 If <path> is not set, the current root will be displayed.
  
  nvm version                  : Displays the current running version of nvm for Windows. Aliased as v.
  
  
  ## LIST VERSION
  
  C:\Users\admin>nvm list

  * 11.11.0 (Currently using 64-bit executable)
  
    10.13.0
    
    12.11.3

## UNINSTALL

C:\Users\admin>nvm uninstall 10.13.0

Uninstalling node v10.13.0... done


## NVM LIST

C:\Users\admin>nvm list available

|   CURRENT    |     LTS      |  OLD STABLE  | OLD UNSTABLE |
|--------------|--------------|--------------|--------------|
|    15.9.0    |   14.15.5    |   0.12.18    |   0.11.16    |
|    15.8.0    |   14.15.4    |   0.12.17    |   0.11.15    |
|    15.7.0    |   14.15.3    |   0.12.16    |   0.11.14    |
|    15.6.0    |   14.15.2    |   0.12.15    |   0.11.13    |
|    15.5.1    |   14.15.1    |   0.12.14    |   0.11.12    |
|    15.5.0    |   14.15.0    |   0.12.13    |   0.11.11    |
|    15.4.0    |   12.20.2    |   0.12.12    |   0.11.10    |
|    15.3.0    |   12.20.1    |   0.12.11    |    0.11.9    |
|    15.2.1    |   12.20.0    |   0.12.10    |    0.11.8    |
|    15.2.0    |   12.19.1    |    0.12.9    |    0.11.7    |
|    15.1.0    |   12.19.0    |    0.12.8    |    0.11.6    |
|    15.0.1    |   12.18.4    |    0.12.7    |    0.11.5    |
|    15.0.0    |   12.18.3    |    0.12.6    |    0.11.4    |
|   14.14.0    |   12.18.2    |    0.12.5    |    0.11.3    |
|   14.13.1    |   12.18.1    |    0.12.4    |    0.11.2    |
|   14.13.0    |   12.18.0    |    0.12.3    |    0.11.1    |
|   14.12.0    |   12.17.0    |    0.12.2    |    0.11.0    |
|   14.11.0    |   12.16.3    |    0.12.1    |    0.9.12    |
|   14.10.1    |   12.16.2    |    0.12.0    |    0.9.11    |
|   14.10.0    |   12.16.1    |   0.10.48    |    0.9.10    |
