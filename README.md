# The-Script-That-Wouldn-t-Run
🔧 Linux Troubleshooting: The Script That Wouldn’t Run 

📜❌ A teammate said, “The script runs for you, but not me!”

 Here are the following steps to troubleshoot:

                 ls -l script.sh 
                 
   I checked groups username — they weren’t in the right group.     

                 usermod -aG <group> username,
                 chmod +x, or chgrp.
        
