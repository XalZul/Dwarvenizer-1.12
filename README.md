# Dwarvenizer edited by Xal-Zul (Zeran) to work in WoW 1.12 (Vanilla). The software belongs to the original author (see below).

---

DWARVENIZER / TROLLIZER
Written by carlo@zottmann.org
Param of Steamwheedle Cartel EU (currently on hiatus)


IF YOU'RE ALLIANCE: Translates/mutilates your written word into something
Flintlocke could've typed. Oh aye!

IF YOU'RE HORDE: Translates/mutilates your written word into something Sen'jin
could've carved in a stone. Ya, mon!

I've tried to incorporate some randomness; play around with it a bit, type the
same thing a few times, and you'll see what I mean.

Example (Dwarven slang -- /dwarvenizer):

    "Ah, Loch Modan. Always a great sight for my old eyes. Everything so neat
    and tidy, and the few beasts around here... we'll be taking care of them in
    no time."
     
     ...becomes...
     
     "Ah, Loch Modan. Always a great sight for me old eyes. Ev'rythin' so neat
     and tidy, an' tha few beasts around 'ere... we'll be takin' care o' them in
     no time."

Example (Troll slang -- /trollizer):

    "Yes... I will kill you now."
    
    ...becomes...

    "Yah, mon... I be killin' ya now."

Your mileage may vary, depending on your Dwarvenizer/Trollizer settings and
randomness.

Also, I clearly consider this an RP enhancement addon. If you can't or don't
type straight, it won't do you much good anyways.

Works in every private, local or group channel (say, whisper, party, guild etc.)
and numbered standard channels (general, trade etc.) from 1 to 4. If a line
starts with "((", it is considered OOC and left alone. If you want to change the
channel settings, type '/dwarvenizer toggle' or '/trollizer toggle'.

Remember: while you're writing straight English, your written word will be
actually "mutilated" prior to sending it. It's not just cosmetic.

When it's first loaded, it's in Dwarvenizer mode. To switch, type "/trollizer".
If you want to switch back, type "/dwarvenizer".

For options and (somewhat sparse) in-game help, type "/dwarvenizer" or
"/trollizer".

Written by Param of Steamwheedle Cartel (EU). Coin donations welcome! If you're
Horde, ping Ambea.

---

Sorry, no screenshots since there are no added or changed UI elements.

---

Little background here: I mainly wrote this for two reasons: one, I thought it
might be a fun little addon, nothing more, nothing less. And two, I wanted to
know whether I could write an addon in LUA, a language I never had any business
with in the past. (I could.) This took roughly three evenings to do so far, so
bear with me. :)

Slash commands (replace "/dwarvenizer" with "/trollizer" if you want to babble
in Trollish):

- /dwarvenizer (prints an overview)

- /dwarvenizer chance [0-10] (set processing probability from 0 (never) to 10
(always))

- /dwarvenizer toggle (show which chat channels are processed right now)

- /dwarvenizer toggle list (same as above)

- /dwarvenizer toggle say (enable/disable vincinity chat (say) channel
processing)

- /dwarvenizer toggle whisper (enable/disable whisper processing)

- /dwarvenizer toggle channel (enable/disable general channels (general, trade
etc. - channels 1 to 4) processing)

- /dwarvenizer toggle party (enable/disable
party channel processing)

- /dwarvenizer toggle guild (enable/disable guild
channel processing)

- /dwarvenizer toggle yell (enable/disable yell processing)

- /dwarvenizer toggle raid (enable/disable raid channel processing)

---

ATTENTION: Turns out Dwarvenizer/Trollizer is incompatible with RPfilter (or the
other way around). If you try to run them at the same time, you might be unable
to send out any chat messages.
