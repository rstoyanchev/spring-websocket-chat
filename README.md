spring-websocket-chat
=====================

Chat application using AngularJS and Spring WebSockets (STOMP over WebSockets)
(A fork from @sergialmar's version)


## Features
- User login
- Chat message broadcasting and private messages (filtering profanities)
- Presence tracking sending notifications when users join / leave
- Broadcast notifications when users are typing
- WebSockets stats exposed at /stats
- WebSocket security

## Configuration
install gradle 

On Mac, just use homebrew 
http://stackoverflow.com/questions/28928106/install-gradle-on-mac-os-x
command in terminal: 'brew install gradle'

Once gradle is installed, issue build command or you can directly run it via
'gradle tomcatRun' command.

## Importing code in eclipse IDE
Install gradle plugin (buildship) from eclipse marketplace.

Once done, Import code directly from github or 'git clone' it first and then import as a gradle project.


## Running the app

gradle tomcatRun

## Debugging the app

use terminal and fire command: 
export GRADLE_OPTS="-Xdebug -Xrunjdwp:transport=dt_socket,address=9999,server=y,suspend=n"

After that, simple run using 'gradle tomcatRun'

Now, 9999 port can be used to listen for debugging via eclise. 

Happy Learning!