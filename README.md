# wayland-lightweight-floating-desktop
## Disclaimer
The opinions here regarding software are personal and I don't try to harm anyone.
I feel that the MIT license suffices the aim/scope of this simple repository.

## Table of contents

## What's this?
This is a repository containing information of interesting software that could allow you to build a lightweight floating desktop that uses Wayland.

I've always wanted to run Linux on my work environments, but I always found that the current desktops available eat a lot of resources neither are modern/Wayland-compatible.

This frustrated me a lot. I understand that this is how the open source world is, everyone collaborates for its own interest, so you must collaborate. Unfortunately not everyone has broader knowledge of low-level programming languages (like me), so this makes it hard to contribute in the development, in this case, of the adoption of Wayland in Linux desktop environments.

In addition, the current desktops that have fully Wayland support plus a big stack of applications (mainly GNOME and KDE) I personally feel that are very resource consuming/memory eaters.

I don't aim to run a modern desktop on a potato computer, but I rather want the performance of my computer to be available for the programs rather than to the DE's animations and menus.

Don't get me wrong, I love how consistent GNOME and KDE app stacks are as well as the desktops are very complete. But I feel that they're bloated plus they waste a lot of my computer memory on just visual stuff (I have 8 GB of RAM and at least GNOME eats 2).

## How can I achieve this?
If you've made till this section, it means you may have some interest in what i'm talking about or may feel like I do regarding Linux DE's, so, here's how you could "build" your own Wayland floating DE.
Keep in mind that building something like a DE based off independent components is something very time-consuming, so yeah you may be very bored if you really want to do this.

### The init drama
First, here comes the usual discussion that nowadays is a lot asked between advanced and non-advanced Linux users before installing a distro (doesn't apply (most of the times) to newbie users).
`sHoUlD i UsE sYsTeMd???`

It's up to you if you want or not to use it.

As well that I'm nobody to tell you to use it or not, neither you should only make up your decisions based on what I've written below. Please search more on this topic so you can make a complete decision and determine your position on this topic.

Some cases where you may not want to use systemd:
- You don't adhere to how systemd is (monolithic but at the same time not*) as well as you like a lot [the Unix philosophy](https://en.wikipedia.org/wiki/Unix_philosophy) (which is very settled on the Linux world but this last decade hasn't that much), then I guess you should use [an alternative](https://nosystemd.org).
- You run a potato or want the init to remain simple and lightweight, as well at the same time you don't care about loosing essential systemd features that lots of mainstream distros use (although you could replace them by other software).
- You don't know a shit about how much drama has the Linux world but still want to avoid systemd because others on Reddit/Matrix/IRC/Discord/Hacker News/-include other chat platform- have told you to do so.

If still you are unsure about using or not systemd, you should know this:
- A lot of Linux software nowadays is written with only systemd on mind.
- Software that heavily depends on systemd would be a very big burden to port to other inits (if you've thought of doing this).
- You'd need to find a replacement for all/most of systemd modules.
- Why are you still reading this repo?
- Other inits don't have that much _fancy_ security features that systemd provides (although some times implemented in a very regular way*).
- If some hacker on the net discovers how to hack your Linux computer (seriously why would it do it?) and somehow fuck up your systemd, say bye bye temporarily to your entire computer as systemd manages lots of other things, not just the init.
- You're loosing your time digging on the Linux world seriously (don't end up like me creating this repo because of my frustration).
- Systemd is very stable though and should suffice the basic stuff without you breaking your head trying other inits.

If you still want to try another init that isn't systemd (as well as find alternative to most of its modules), below is the info:
-

I'm not going to go more deep than here about this topic, if you want to find more info about the entire drama just search (on your preferred search engine) keywords such as `systemd`, `the systemd drama` or `should I use systemd?`, just to name a few.

Wikipedia has you covered too: https://en.wikipedia.org/wiki/Systemd, as well as [this website partially](https://nosystemd.org).

### The (UI) tookit drama

### Distros

### Wayland compositors

### Essential software (panels, docks, OSDs, file managers...)

### Other software

### Gaming

### Benchmarks (and how you shouldn't make up your decisions based on only them)

### Other resources that you may be interested in
