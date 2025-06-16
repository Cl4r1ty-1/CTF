# misc/sky

In this challenge, we are given a picture that we need to find the location of. Once we find the longitude and latitude coordinates of where this photo was taken, we need to submit them to a program to print the flag for us.

![[challenge.png]]

Initially I chucked the photo into google images to see if I could find anything, however it seemed too be very obsessed with the type of tree.

![[init_search.png]]

So I decided to just ask it straight up.

![[w_strat.png]]

Amazing strategy I know.

Anyway after coming across this image from a coffee shop in Bahrain I was convinced that wherever this was, was the answer.

![[bh_coffee.png]]

Which led me down a rabbit hole of finding the shop and submitting the coordinates of that for a few tries. After getting sick of copying a POW script about 10 times it was obvious that I needed to look elsewhere.

That's when I came across this image taken in UTC Mall, San Diego

![[nearly_there.png]]

Which looked more similar to the challenge image, so I decided to go and find that.

![[yippee.png]]

After copying the coordinates of this place from google maps, putting them in the correct format for the program and submitting them, I get the flag.

```
┌──(kali㉿kali)-[~/Downloads/sky]
└─$ nc smiley.cat 37867
proof of work:
curl -sSfL https://pwn.red/pow | sh -s s.AAA6mA==.7/SJBDRgwBS4CjhngHesjQ==
solution: s.e9+ET8njUWJMYDskDM+D5+TcU/hu10yQCqbFUlEoIAiUWOG1yNMlr43HerCZ/n4xSzyP0+6s7swOSVoIFAy5f+hag/YL1RETldOMOK5gfJgqTg8gRDR+nuuFaCwB7rDB0oaIJTWsllO/aEvuwKl5hymJun0w2SF2DduuzTWUYZCVdtXk4TvYZMxKSFJHcIYdHjRfe+JBlVo6gpDYhhpbGQ==
Please enter the lat and long of the location: 32.87114921627872 -117.21136486880005
Correct! You have successfully determined the position of the camera...here comes the flag
Great job, the flag is  .;,;.{g00gl3_ai_th1nks_th3s3_pr0duc3_r3n3w3bl3_3n3rgy_1ma0}
```

Flag: `.;,;.{g00gl3_ai_th1nks_th3s3_pr0duc3_r3n3w3bl3_3n3rgy_1ma0}`

