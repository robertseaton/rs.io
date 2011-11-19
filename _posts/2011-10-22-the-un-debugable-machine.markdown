---
title: The Un-debuggable Machine
layout: post
hidden: true
---

I get along well with most pieces of technology (not counting [my smartphone](http://rs.io/2011/10/19/i-hate-my-smartphone.html)) and I make a capable troubleshooter, but there’s one piece of hardware where the slightest hiccup leaves me with a deep sense of foreboding. 

Maybe you’ve guessed it: the printer. 

### If the Three Gorges Dam is a marvel of modern engineering, the printer has to be one of its blackest marks. 

I’m getting ready to junk another printer, part of a long line of now defunct devices. I’ve heard a number of stories from fellow nerds about faithful desktops, aged more than ten or fifteen years, that they’ve had to either junk or relegate to the basement since their machine’s hardware, still in working order, is just too dated. My own desktop has lasted more than 5 years and I still use it every day.

I have heard no such stories about printers, though, and I’ve never personally had one last more than two years. That alone leaves me feeling slightly uneasy about the devices, but what *really* frightens me about the printers I’ve owned, gentle reader, is that they are seemingly impervious to debugging attempts.

When you first buy a printer, you’ve got the pain of the initial setup to deal with. A task that can prove to be no small feat if you’re dealing with anything other than mainstream hardware. What, you want hook up your fancy wifi-enabled printer so that it’s shared over a network served up by a custom-built BSD router and you want the ability to print from Windows, OSX, and Linux machines? You’re in for a world of hurt. 

### I couldn’t figure that out even though I’ve made it through a number of Gentoo installs.

Eventually, I gave up. I bought a standard router (well, kind of, it’s a Netgear WNR3500 running dd-wrt) and I was limited to printing from the Windows machines. By that point, though, the fight had been beaten out of me and I was happy to be able to print at all.

Don’t have a disk drive and you’re planning on downloading the drivers? God help you, you’re well into the belly of the whale. I remember thinking: “Is this *really* the manufacturer’s site or just a clever attempt at serving up malware?” The site was that shady.

Things worked okay for about six months, and by “okay”, I mean that every once in a while the print queue would block on some phantom task but, thanks to a trick learned long past from Microsoft support, it’s just a quick trip to services.msc, kill the printer spooler, and you’re ready to go. Until it all breaks down again, then rinse and repeat. 

Then, once that six month mark rolled around, printing quality started to degrade. The printed pages were still readable, but random lines would be half-italicized. I tried re-installing the printer drivers, re-aligning the print heads, everything. I read the suggestions in every E-how article I could find. 

Nothing fixed it. Eventually, I just gave up, again. The machine still printed okay, readable, at least, just slightly garbled. The printer had defeated me, master debugger, twice, as all its brethren had defeated me years prior.

As of about a week ago, the machine has started to really go mad. Whole pages are lost or garbled, while others print fine. You might have to print a document five times to get one complete, legible copy of your work. Again, I haven’t got the first clue how to fix it. 

Suffice to say, I’ve had enough headaches debugging this machine. I’m just going to write it off as a lost cause, take it out to a field somewhere, and, well, [you know](http://www.youtube.com/watch?v=l0_S_EdZ_I8). Then I’ll buy a new one and start the entire process over again.

The sorry state of printer technology is baffling. I wonder: how do consumers manage to print anything at all? I can barely comprehend the suffering of the IT guy who is responsible for keeping an institution’s printers in working order. That surely must be the inner-most circle of Hell.
