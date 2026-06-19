
Open PS as admin
Start the ssh agent with the following commang : Get-Service -Name ssh-agent | Set-Service -StartupType Manual

Then go on to use ssh-add to add the newly generated ssh key to the ssh agent.