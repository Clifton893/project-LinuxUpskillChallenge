# Case Study: Linux Upskill Challenge
[ Description ]

### Outline
- Intro
- Methods
- Learning
- Conclusion
  - Breakthroughs
  - Room for improvement

## Intro
[Always save your intro for last]

## Methods
As a casual Ubuntu user for a decade, I had been looking for exercises to better myself at system administration (particularly at the CLI level).

After some searching, I found something called the “Linux Upskill Challenge,” which caught my attention. Originally a paid course, it was now a free, month-long exercise in remotely administering an Ubuntu Server instance.

The way it was set up, “students” studied/performed an activity and themed lesson each weekday, over the span of a month. Rather than dally and take my time, I finished in [x days].

Basically, each “day’s” lesson consists of a set of tasks, a relevant glossary, and extended reading links, all accompanied by a video for additional context.

I thought it was pretty cool, since it was a clever way to get your hands dirty and have some direction.

## Learnings
I had used Google Cloud Platform previously, but this was my first exposure to Amazon Web Services, so getting some exposure to its dashboard and UI was good.

Another first was using SSH, and this project was a great way to get my hands comfy to the process. Even though AWS provides the public and private key -- thus precluding `keygen` -- going into `.ssh/config` to set up a smooth connection was definitely good practice. `ssh -i [path] [key]` is no way to regularly remote into a system.

Opening all your ports (as per instruction) was another fun change of pace. Going into `auth.log` and `journalctl` and seeing the thousands of would-be attackers was neat, and helps drive home just how hostile the Internet is.

Sending files over SFTP, installing an Apache web server, and configuring `ufw` were also super-useful utilities to get some practice with, too.
