# SpotifyBot_test
This soon will become first deployed version of SpotifyAnalyzer bot, which main goal is doing funny thingies with music.
## Usage
Prefix for commands is _"!"_.
Here is the  small list of stuff it can do : 
Command (and syntax)| What it does
------------ | -------------
!listen (int n) | Invokes async command, which lasts for (int n) minutes, and checks current users Spotify discord activity, returning you simple analyzis in embed (NOTE : Your spotify must be connected to discord)
!listen (int n, SocketUser user) | Overload, checks activity of custom @user.
!search (string search_request) | Returns basic request values, taken from Spotify WEB API.
!test | A test command, but will show you what you listen to.
!help | Just tells you what a douchebag you are in DMs.
