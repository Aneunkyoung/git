## ๐ป My First Time Git

> Github ์ ์ ๋ฐ ๊ฐ์

โก๏ธ Your repositories โ new โ Repository name: Medicines โ Public โ Create Repository

<br>

> terminal

โก๏ธ $ brew install git โ git ์ค์น.

โก๏ธ $ git config --global user.name โAneunkyoungโ โ Github push์ฉ ์ด๋ฆ ์ธํ.

โก๏ธ $ git config --global user.email โlindsayan991128@gmail.comโ โ Github push์ฉ ์ด๋ฉ์ผ ์ธํ.

โก๏ธ $ git config --list โ Github push์ฉ ์ด๋ฆ ๋ฐ ์ด๋ฉ์ผ ํ์ธ.

โก๏ธ $ cd /Users/eungyeongan/Desktop/medicines โ push ํ  ํ๋ก์ ํธ ํ์ผ์ ์ ์.

โก๏ธ $ git init โ push ํ  ํ๋ก์ ํธ ์ด๊ธฐํ.

โก๏ธ $ git add . โ ํ์ฌ ๋ฐ ํ์ ๋๋ ํ ๋ฆฌ ๋ชจ๋ (.) ํ์ผ index ์ถ๊ฐ.

โก๏ธ $ git status โ ํ์ผ์ด ์ ๋ฑ๋ก๋์๋์ง ํ์ธ.

โก๏ธ $ git commit -m "first commit" โ local repository์ ์ถ๊ฐ.(ํ์คํ ๋ฆฌ ๋ง๋ค๊ธฐ) โ ex) ์ต์ข, ์ง์ง ์ต์ข, ๋ง์ง๋ง ์ต์ข, ์ฐ๋ง

โก๏ธ $ git remote add origin https://github.com/Aneunkyoung/medicines.git โ ๋ด ํ๋ก์ ํธ์ ๊น์ ์ฐ๊ฒฐ๊ณ ๋ฆฌ.(์๊ฒฉ์ ์ฅ์์ ์ฐ๊ฒฐ ์ธํ)

โก๏ธ $ git remote -v โ ์ฐ๊ฒฐํ ์ฃผ์๊ฐ ๋จ๋ฉด ์ฑ๊ณต.

โก๏ธ $ git push origin master โ remote repository์ ์ถ๊ฐ.

<br>

## ๐ป Eclipse๋ Git ์ฐ๊ฒฐํ๊ธฐ

1. ์ฐ๊ฒฐํ๊ณ ์ ํ๋ ํ๋ก์ ํธ๋ฅผ ์ค๋ฅธ์ชฝ ๋ง์ฐ์ค ํด๋ฆญ.
2. Team โ Share Project โ Use or create repository in parent folder of project ํด๋ฆญ โ ํ๋ก์ ํธ ํด๋ฆญ โ Finish
3. ๋ค์ ํ๋ฒ ํ๋ก์ ํธ ์ค๋ฅธ์ชฝ ๋ง์ฐ์ค ํด๋ฆญ.
4. Team โ Commit โ Add selected files to the index(+ ๋ฒํผ) โ Commit Message: This is Commit Mesasge โ Commit and Push
โ Repository: https://github.com/Aneunkyoung/medicines.git โ User: Aneunkyoung , Password: โ Login

<br>

> rejected - non-fast-forward ์ค๋ฅ ํด๊ฒฐ

1. Window โ Show View โ Other โ Git Repositories
2. ์ ์ฅ์ Remotes โ origin - github ์ฃผ์ ์ฐํด๋ฆญ โ configure Fetch 
3. Advanced โ ๊ธฐ์กด์ ์กด์ฌํ๋ Source Ref Remove(ํด์งํต ํด๋ฆญ) โ source ref: master[branch] โ Add Spec โ Finish โ Save and Fetch
4. Branches โ Local - ๊ฐ์ง ์ฐํด๋ฆญ โ Merge โ Merge
5. Team โ Remote โ Push โ Next โ source ref: master[branch] โ Add Spec โ Finish
* ์ฐธ๊ณ : https://hanyda.tistory.com/m/36
