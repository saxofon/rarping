# Rarping on the road to 0.1 stable #

As you know, I'm trying to give RARPing enough maturity to talk about a "stable" software.
But I continue to add features to RARPing, recent ones are

  * -q : RARPing exits (success) after the first received reply
  * -s [IP address ](.md) : spoof source IP address

(and RARPing use now the real IP address, instead of 0.0.0.0, in sent packets)

I maintain a TODO file (look at the SVN) with ideas I have about the project. The one I am currently working on are MAC address correlation (prefix <=> vendors) and reverse DNS resolution on IP addresses contained in replies.