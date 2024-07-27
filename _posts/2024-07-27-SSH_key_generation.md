# Steps To Generating and Adding a New SSH Key

I recently bought a new computer and needed to connect it to GitHub. It's been a while since I had done this so it took me a few hours to get it done. I'm wirting it done so you and I don't have to spend countless 
hours of research next time.

### Steps To Gwnerate a New SSH Key
1. Open Git Bash
2. Paste the following command: ssh-keygen -t ed25519 -C "youremail@domain.com"
   - Replace the generic email with the email address you have in GitHub
3. Click enter to save key in suggested location
4. Create a passphrase and enter it
   - write it down somewhere safe that you can access
   - you will be asked to type it in twice
6. Then run this command: clip < ~/.ssh/id_ed25519.pub
   - The system will copy the SSH key to your clipboard to then copy in Github

### Steps To Add New Key To GitHub
6. Add the new SSH key to GitHub by going to your settings > SSH Keys & GPG Keys > New SSH Key
7. Add a relevant title for SSH key... example "Personal Laptop 2024"
8. Paste the SSH in the "Key" section

The device should now be added and connected to GitHub!

Cheers,

Gaby
