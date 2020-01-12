# InfosecCTF

Im not very good at writing i just want the money.

So, the first level. Yoda says may the source be with you.

Maybe we should check the source?

Ctrl-shift-i and we see at the very top a comment <!-- infosec_flagis_welcome -->

We found it!


LEVEL 2:

Ok now it's time for level two. Hmmmmm the image is broken HUH?

Ok yes it might be but i don't trust it. So im opening up burp suite community edition to check this out.

I see the file in the Target tab and I send that to the repeater. At the bottom I see a suspicous looking thingy ma bob.
aW5mb3NlY19mbGFnaXNfd2VhcmVqdXN0c3RhcnRpbmc=

What is that
I see the equal sign at the end.
IT MIGHT BE BASE64!!!!!!

Ok i pop that into a base64 decryptor: https://www.base64decode.org/
and get: infosec_flagis_wearejuststarting

yay!

LEVEL 3:
