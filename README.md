# networkqualitymonitor
Network quality monitoring menu bar indicator for MacOS

## What is it

A MacOS Swyftbar plugin that displays the network latency (ICMP rount trip time) to a specified IP target in the Menu bar

![MacOS Menu bar](/img/menubar.png)

## How to install

### Prerequisites

-Install SwiftBar
    Download from [GitHub Releases](https://github.com/swiftbar/SwiftBar/releases)

    or Install with Homebrew

    ```
    brew install swiftbar
    ```

-   Install networkqualitymonitor plugins

    ```
    git clone https://github.com/slartibastfast/networkqualitymonitor.git
    ```

    Create a plugins folder and copy plugins to it
    e.g.

    ```
    mkdir ~/Library/SwiftBar/Plugins
    cd networkqualitymonitor
    cp Plugins/* /Library/SwiftBar/Plugins
    ```

### Configuration

-   Launch Swiftbar from Applications
-   Choose Plugins folder
-   Modify the plugin file name to change the refresh interval, refer to Swiftbar documentation for configuration details, https://github.com/swiftbar/SwiftBar


### Credits
Thanks to the folks at:
- https://xbarapp.com/
- https://github.com/matryer/xbar-plugins
- https://github.com/swiftbar/SwiftBar
- https://github.com/jasonsnell?tab=repositories

