"""
Procedura za push-at na GitHub:

1) odpri Git Bash 
2) Vpiši svoje ime in email (da bo zgodovinski arhiv lahko beležil, kdo je spreminjal kodo)
3) git config --global user.name "John Doe"
4) git config --global user.email johndoe@example.com
5) Naredi novo mapo za svoj projekt
6) V mapi klikni z desno miškino tipko in izberi Git Bash here
7) V Git Bashu izvedi te ukaze, ki si jih prej videl na spletni strani (POZOR: URL projekta pri git remote add origin bo drugačen, kot pa je prikazan spodaj!)
8) echo "# test" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/ramuta/test.git

git push -u origin master

9) Poglej na spletno stran projekta na GitHubu in videl/a boš, da je tam nov dokument README.md

"""
