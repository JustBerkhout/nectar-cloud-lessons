## Activity

# Launch RStudio Server

### Prepare
* Log in to your NeCTAR Dashboard, and if you have access to more than one allocation, ensure that your project selector (top left on the Dashboard, is set to the project of your choice).

You will need a Security Group with a rule that allows your instance to receive instructions on port 8787. If you have a suitable Security Group, you can skip the remainder of this section. This acitivty assumes that you have a Security Rule that allows SSH traffic.


* On the "Access & Security" |"Security Groups" page, Create a Security group called "RStudio" (or similar) containing a Custom TCP Rule that allows Ingress on port 8787. (Leave the Remote CIDR to be set to 0.0.0.0/0)


### Launch RStudio
* on the "Instances" page open the "Launch Inistance" Dialog
* fill in:
    * details: [Your Rstudio Name] (Pro Tip: a lowercase name without spaces works best), Flavour M2.Medium, Image Name "TPAC rstudio.010 xxxxxxxxxxx"
    * access & Security: Your Key Pair, your ssh group and your rstudio security group
    * availability Zone: Tasmania
    * (verify all these settings, then click Launch)
* (while Nectar is scheduling/building/spawning your instance, see if your neighbour needs a hand. Alternatively, talk about your w/e plans)
* when launching is complete (i.e. your instance shows its Status = Active) note its IP Address.

### Create a user account
* connect to your instance using `ssh -i /path/to/your/key.pem ubuntu@youripaddress` (<-- adjust for your situation)
* choose a username (Pro tip: Align with an existing username you already have? Or use your firstname? e.g. `jdoe`)
* when connected create a user account using your chose username like this: `sudo adduser jdoe` 
* choose a suitable password (be sensible! Do not use a high value password you use elsewhere. Why?)
* (fill in the requested details, or leave blank if you choose. Answer Y for the "is this correct" question)
* Note and/or remember both the username and password

### Connect to RStudio Server
* open a browser RSudio recommends as a minimum: Firefox 10, Safari 5.1, Google Chrome 20, Internet Explorer 10 (or up)
* navigate to your instance, using `your.ip.add.ress:8787` (<--note the `:8787` after your ip address)
* the RStudio server will display a sign in form. Sign in using the Username and Password you created above.
* install a package (e.g. `install.packages("gapminder")`)


This concludes this activity