# Auto Profile

## Commands

- **Rotating Profile Picture**
[Syntax: `autopfp <x> <y>`]

  Rotates your profile picture every 60 seconds with x degrees.
  
  x (degrees) - The ammount by which the profile picture should be rotated.
  y (True/1/False/0, case sensitive) - If True, the previous profile picture is deleted from your profile after a new rotated profile picture is generated. Handy for those who don't want to flood their profile with similar pics.
  
  Example: `.autopfp 30 True`
  Rotates the current profile pic by 30 degrees every minute and makes sure that only one of the rotated profile pic remains in the profile.

  Use `stopautopfp` command to stop rotating your profile pic, in case you feel dizzy. xD

- **Automatic bio changer**
[Syntax: `autobio <x>`]

  Updates your bio every 60 seconds with the current time, x is the custom formatted bio with a `{time}` placeholder to show the current time.
  
  Example: `.autobio Hello stranger, it's {time} o'clock.`

  Updates your bio every minute with the message format: ***Hello stranger, it's 11:59 o'clock.***

  Use `stopautobio` command to switch this feature off.

- **Automatic name changer**
[Syntax: `autoname <x>`]

  Updates your display name every 60 seconds with the current time, x is the custom formatted name with a `{time}` placeholder to show the current time.
  
  Example: `.autoname I'm {time}.`

  Updates your name every minute with the message format: ***I'm 05:00.***

  Use `stopautoname` command to switch this feature off.

- **Delete profile picture(s)**
[Syntax: `delpfp <n>`]

   Deletes the previous n profile pics from your profile. If n is 'unlimited', it deletes ALL your profile pics.
  
  Example: `.delpfp 5`
  Deletes the last 5 profile pics from your history.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyMjY5MTYzMDVdfQ==
-->
