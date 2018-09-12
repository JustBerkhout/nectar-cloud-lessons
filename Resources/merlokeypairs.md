# Key pairs

or

# How to remember a 1500-random-character-password

To be able to use the Nectar Cloud you will need a Key Pair.

What a key pair is, how they work, why you need one and how you get one are the subjects of many religious texts and colourful anecdotes. But for us, today, this is what that boils down to. 

## What is a key pair?
A key pair is essentially a pair of files, consisting of:

1. Your **Private Key**: your very own 1500+ random character password
2. Your **Public Key**: a string of characters that uniquely identifies the Private Key, but isn't the same!

3. A third essential component here is **software** to handle them both, so you don't have to remember and type so much ;-). The software we'll use for this is **ssh**.

## How do they work?
> Say you are Merlo Pisum, a researcher in linguistics. You want access to your language institute's supercomputer _Deep Green_. The sysadmin tells you to email them your _*Public Key*_. After you have sent your public key to the sysadmin, they create an account on _Deep Green_ with your username. When this is complete, the sysadmin sends you the following connection details:
> 
* hostname: deepgreen.myinst.edu.org
* username: merlo

> The connection instructions for ssh say:

`ssh -i /path/to/your/privatekey.file merlo@deepgreen.myinst.edu.org`

Other software will use similar connections details. You usually specify a servername/hostname, a username, and your *_Private Key file_*

## Why?
Private Keys (ie. 1500+ character random character passwords) are incredibly hard to guess, even for incredibly powerful computers. 

Private Keys are equally hard to remember, so they must necessarily be a file. 

**!! A file that you guard well!!**

I could list many benefits of key pair security, but you would probably not believe me, so it's best to leave is at this:

Launching Virtual Machines in the Nectar Cloud **requires** that you use a Keypair.

Now that you're convinced

## How do I get one!
Nectar's convenience method.
Nectar can generate a keypair for you.

Go to [http://tinyurl.com/creating-a-keypair](http://tinyurl.com/creating-a-keypair)
