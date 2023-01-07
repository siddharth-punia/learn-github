http://cb.lk/11septweb


1. git ko allow karna version manage krne k lie -> git init
"dir -force" to show hiddden files
2. to see kon kon si file change hui hai ya koi new file create hui hai ya nahi we use -> git status

staging area - jo jo file ko version mai add karna hai use yaha add kro -> git add <file>
sbhi files ko bhejna ho add krna ho to -> git add .
agar staging area se hatana ho to -> git rm --cached <file>

git commit -> ham ye krte h or iske sath ek message daaalte hai taaki pat chle ki kya chnages kie the us samay

git config --global user.name “[firstname lastname]” -> to configure name
git config --global user.email “[valid-email]” -> to configure email

in vim ->
press i -> insert
then add text "creating a file to wish merry christmas"

baahar jaane k lie ->
1. esc button
2. ":wq"

master (root-commit) 1472149 -> master branch par commit kara hai or uski id hai 1472149

 # git add -A -> sarri file add krdo

 **git commit -m** "creating a file to wish happy new year" -> jo kaam vim se kia uska shortcut

 delete file1.txt
 git add -A
 git commit -m "christmas tree ka message daala or file1.txt ko delete kr dia"

 jese jese commit krenge new version bnta jaeega

 abhi tak jo jo kia us dekhne ke lie -> git log

 commit d6c564d4056095805f8a511edc23434c4a9d1c3c -> commit id

 latest version -> master

 git checkout 15489c93d0e2ff669f708ef14c5ed41284ebb46e -> isse jo version m changes hue vo aajaenge
 is id pr switch ho gye

 git checkout master -> Switched to branch 'master'

jab bhi ham code change krte hai vo master branch m change nai karte
master branch m change nahi karte, branch kaat te hai
jis node m khade hoke branch bnai us branch ma file aajaegi
git branch-> check current branches


# to create new branch
1. git branch oggy

master se oggy par shift karna hai to -> git checkout oggy

1. make changes in the file
git add -A
git commit -m "changes in oggy"
git checkout master -> master pr ajao or yaha se merge krdo
git merge oggy -> merge kr dia

git branch -D oggy -> delete

branch banane ka chota tareeka or uspar jaane ka bhi ->
git checkout -b <filename> -> Switched to a new branch 'chotabheem'


chotabheem branch ka merge krne k baad koi kaam nhi, use delete krdo

q -> quit