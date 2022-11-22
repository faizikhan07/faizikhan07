- 👋 Hi, I’m Faizan Khan alias Faizi Khan
- 👀 I’m interested in Full Stack Development 
- 🌱 I’m currently learning Python, JavaScript, React JS, Angular JS, GIT & GITHUB
- 💞️ I’m looking to collaborate on Software Development 
- 📫 How to reach me ... Official Mail Id: faizankhancse1@gmail.com

# GITHUB SSH KEY CONFIGURATION STEPS FOR WINDOWS USERS

## GENERATING A NEW PUBLIC/PRIVATE SSH KEY

1. Generating a new SSH key
> $ ssh-keygen -t ed25519 -C "your_email@example.com"
NOTE: If Above command or ed25519 doesn't work, use this below:
> $ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
> Generating public/private ALGORITHM key pair under the default location: /c/Users/YOU/.ssh/id_ALGORITHM
2. Start the ssh-agent in the background
> $ eval "$(ssh-agent -s)"
> Agent pid 59566
3. Add your SSH private key to the ssh-agent.
$ ssh-add ~/.ssh/private_key_name

## ADDING A NEW SSH KEY TO YOUR ACCOUNT

1. Copy the SSH public key to your clipboard
$ clip < ~/.ssh/public_sshkey_name.pub
2. go to account in github > ssh keys > add key > paste copied content
3. Clone a repository and known_hosts file will be generated.

## TIP: If clip isn't working, you can locate the hidden .ssh folder, open the file in your favourite text editor, and copy it your clipboard.

<!---
faizikhan07/faizikhan07 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
