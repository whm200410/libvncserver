 This is a clone of libnvcServer, but the original library can't be used on windows platform, I make some modificationt to make it work on windows.
 1. replace all socket type(int on unix, SOCKET on windows)
 2. replace pthead to windows thread.
 
 make sure to enable pthread define after cmake
