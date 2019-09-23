# jobsdone (jd)

[![JOBS DONE](https://img.youtube.com/vi/5r06heQ5HsI/0.jpg)](https://www.youtube.com/watch?v=5r06heQ5HsI)

[Click this for a surprise ☝️]

### JobsDone is a simple unix filter command to alert you when a job's done.

Jobs done uses [HyperLink](https://apps.apple.com/us/app/hyperlink-push-enabled-links/id1480418373) to send you a push notification with a customizable message when your job finishes.

# Installation
 1. Use pip (and Python 3) you lout.
  * ```$ pip3 install jobsdone```

# How to use it
 1. Install and open [HyperLink](https://apps.apple.com/us/app/hyperlink-push-enabled-links/id1480418373) and copy your key. Run:
  * ```$ jd --key YOUR_KEY_HERE```

 2. Run jobs, commands, whatever, and pipe the output to `jd`.
  * ```$ sleep 3 | echo "3 seconds have passed" | jd```
  * Or you can ignore the pipe output and send a custom message
  * ```$ sleep 1 | echo "1 second passed" | jd "YO! One second passed ⏱️"```

 3. That's it. There is no step 3. Go outside.

 