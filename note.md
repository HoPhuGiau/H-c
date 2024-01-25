# cmd

git --version
git config -g user.name

# Terms

Reponsitory (Repo) : thu muc , du an
Branch : mot cai cay se co nhieu canh`
Conflict : Xung dot

# Commands

- git init : lam du an tro thanh mot git

- git status : xem lai trang thai cua du an , xem co thay doi gi

- git add : chuan bi luu lai thoi diem hien tai du an
- git add . : chuan bi luu lai tat ca file

- git reset : khong chuan bi luu nua

- git commit : chinh thuc luu du an, lenh nay can ghi chu truoc khi luu
> git commit -m 'initial commit' : cam ket ban dau, thoi diem dau tien trong luu

- git log : xem lai nhung thoi diem da luu
- git log --oneline

- git checkout {branch name} : tro lai lan commit cua id do
- git checkout master  

- git branch

- git checkout -b {branch name} : tao branch name 

- git merge {branch name} : tong hop lai cac commit

- git branch -d {branch name} : xoa 1 branch

# day du an len github
- git push {dia chi} {branch name} : day du an len github
- git remote add origin {dia chi} : o day co the hieu la origin la ten dia chi do, co the duoc su dung cho viec push nhanh hon
- git push origin {branch name}


# lay du an tu github ve may

- git clone {dia chi} : lay du an tu github ve may
- git push : co the push thang ve github

# day branch len github

- git push -u origin dev
# merge branch
- git fetch origin
- git checkout -b staging origin/staging

- git push -u origin dev

