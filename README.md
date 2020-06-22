# README.md

To change the permissions we can use chmod and chown. 
chown -R cumoja1:amatta1 ~submissions
chmod -R 770 ~submissions~

I copied the document using cp /home/cumoja1/"The Hunger Games" /home/amatta1

to replace a characters name with my name I used the sed command and i used the \b so it would not replace versions of the word and the syntax was:
sed -i 's/\bKatniss\b/Ashlynne/g' The Hunger Games
 
renaming the the file was simple and I used a basic mv command:
mv "The Hunger Games" "My Hunger Games"
