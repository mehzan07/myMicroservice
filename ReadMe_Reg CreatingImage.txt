if
command:
> docker build -t mymicroservice  .  dosent work 
then your Dockerfile has an extension .text
you should run the following command:

>docker build -t mymicroservice -f ./Dockerfile.txt .

then it worked.

or
To create a Dockerfile without .txt:
1- open notepad++ and paste the content to it.
2- save as choose  all type (.) and save the file then your file shall be with out .txt and shall be an executble file.