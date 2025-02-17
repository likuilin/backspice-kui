# backspice-kui

I bought a Twiddler 4. This is my fork of [AlexBravo's Backspice layout](https://github.com/AlexBravo/Twiddler) for my own personal use.

I wish the [Twiddler Tuner](https://tuner.mytwiddler.com/) could export config files in a human-readable flat text layout. Since it only exports binary config files, and it does not have good version control features, it is hard to keep track of modifications.

In this git repo, I will log the changes I make to my configuration. The `current.cfg` file will always be in sync with `current.cfg.xxd` so that there is some sort of diff, at least. In the future, after a good third-party reverse-engineered flat format becomes standard, a future me may reconstruct the history of this project.

## Changelog

* Downloaded "config v5 - for Twiddler 3" [twiddler.cfg](https://github.com/AlexBravo/Twiddler/blob/503218723fd34da5b980b481b90596dbbef76a99/config%20v5%20-%20for%20Twiddler%203/twiddler.cfg).
* Used DDRBoxman's twiddler-cfg conversion tool ([permalink](https://github.com/DDRBoxman/twiddler-cfg/tree/f4f90c8a1a455ce7b537eedeea85f899a53f1d70)) to convert it to Twiddler 4
* Uploaded it to the Twiddler Tuner, and then downloaded it, to normalize any aberrations (there were none).

