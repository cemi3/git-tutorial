# Version control
## Git:
- v git init (เริ่ม project)
- v git checkout branch_name (กระโดดข้ามจุดข้าม branch)
- v git checkout -b branch_name (แตก branch)
- v git branch branch_name (แตก branch, branch)
- v git branch -d branch name
- - git push origin -u --delete branch name (ลบใน git hub)
- v git status
- v git add . (เพิ่ม file ก่อน commit)
- v git reset (เอาไฟล์ออกจาก stage)
- v git commit -m "commit message"
- v git log --oneline
- - git pull (get update from remote / download branches)
- - git push (update to remote * upload branch,commit to github)
- - git push origin -u branch_name
- v git merge target_branch_name (รวม branch ปัจจุบัน เข้ากับ  branch target)


## Git <=> Github:
- v connection:
    - ssh-key (pubkey) => github
        - ssh-keygen
    - add config file

- pull request (ขอเอา branch ย่อย ไป merge กับ branch หลัก)