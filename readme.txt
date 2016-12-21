- klik kanan di folder yang akan di git
- GIT Bash Here
$git init

tambah file
1. $git add name.ext
2. $git touch name.ext
3. echo "text inside" >>name.ext

cek status
$git status

menambahkan ke git
$git add name.ext   	---satu per sat
$git add . 		---semua
$git add *.html		---semua html

setelah ditambahka ketik
$git commit
ketik "i", ketik judul misal Initial Commit, Esc, ":wq", enter

menambah list file yg tidak di p
buat file ".gitignore"
$touch .gitignore

membuat branch
$git branch namaBranch

pindah branch
$git checkout namaBranch

remote
$git remote add origin https:/github.com/zatanabee/LearnGIT.git
$git remote -v
$git commit -a -m 'comment title'
$git push origin -u namaBranch
$git push origin namaBranch

ingat selalu
- git add . 
$git commit -a -m 'comment title'

create a working copy of a local repository by running the command
$git clone /path/to/repository
when using a remote server, your command will be
$git clone username@host:/path/to/repository