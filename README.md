# HackThisSite - Basic 2
## Description
A slightly more difficult challenge, involving an incomplete password script. Requirements: Common sense.

We will be doing Basic 2 from HackThisSite
https://www.hackthissite.org/missions/basic/2/

## Solution
Upon accessing the challenge page, we observe:

`Network Security Sam set up a password protection script. He made it load the real password from an unencrypted text file and compare it to the password the user enters. However, he neglected to upload the password file...`

Although Sam hasn't uploaded the password file, the script will still execute. However, due to the missing file, the password comparison will be ineffective. We can therefore press the submit button and gain access without providing a valid password.
It's a common practice for developers to include temporary comments in their code, which sometimes contain sensitive information that can be accidentally left exposed.

I appreciate you taking the time to review my write-up. If you have any inquiries or comments, please feel free to reach out. See you on the next challenge.








