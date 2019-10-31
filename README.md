# JosRami-VulnHub-PumpkinGarden-Notes
Notes from my assessment on the Pumpkin Garden vulnerable box. (Completed!)
This box was fairly easy to complete.
It started with credential exposure accross the whole system, especially the website being hosted.
Once the credentials were found, access to the other services was granted.
Eventually you could get an exploit that targeted an older version of Sudo on the target system, allowing the attacker to add users to the sudo file.
This was executed on a local user we had credentials for, leading to elevated priveleges and a su to root.

This is not a good example of note taking, I was very disorganized and did not take pictures of the process, look at my second set of notes, Pumpkin Raising for a better example.
