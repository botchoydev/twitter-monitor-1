# tweeper-the-twitter-monitor
Monitors Twitter for new tweets with filter capabilities, lightning-fast using Tweepy's Stream API
 - Multithreaded (can monitor multiple handles without having to run the script multiple times!)
 - Built-in URL expander! (sent after initial tweet, expands typical t.co link into more funcitonal format)

**Get Started:**

 - Sign up for a twitter developer account and create a new app. You will need twitter developer keys in order for this script to function.
 - Replace key sections in devkeys.txt with their respective keys. Please keep the line breaks in the format provided.
 - Run start.exe

To Be Added:
 - Keywords (I dont see a use case but is very easy to implement)
 - GUI (not really necessary but cool project)
 - Logging
     - Documenting all tweets in a database format such as JSON for use in AI training projects (super not Twitter approved but we have workarounds)
     - Options to record additional information such as time, twitter handle, twitter name, bio
 - Send logs to a seperate discord channel in real time (could be beneficial for example if you needed to know as soon as possible if there was an issue with the monitor)
 - Select filters from command line
 - Different filters for different monitors
 - Simultaneous API and non-API implementations (to get tweet the fastest, operate while twitter dev keys arent available, but still have access to private accounts, etc etc
 - Monitor keywords across all of twitter (simple terms, hashtags)
 - Remote operation via webapp

Feel free to leave more feature suggestions as issues :)

**If you are a business owner and don't have a clue on how to proficciently operate this monitor;** I am willing to host it on a server and maintain it for a monthly fee, please DM me on twitter if you're interested!


If you are building from source:

**WORKING ONLY IN PYTHON 3.6!!!** - Use virtualenv! If on windows I prefer PyInstaller :)

*I am not responsible if this is in any way abusing the Twitter API and resulting in you getting your developer account closed.* In its current state it does not collect data or abuse get requests, and the stream API is supported by them because it it less resource intensive, so I think they should be cool with it :) 

***DONT COLLECT DATA WITHOUT TWITTER's EXPLICIT PERMISSION!!! Privacy breaches are not cool, and can lead to more limited API's in future :(***

*But at the same time people who tweet on public accounts should know that their data may as well be public domain, do you own m*
