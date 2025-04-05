# Git Flow
main
│
├─── hotfix/urgent-fix
│       ↳ main + develop へマージ
│
develop
│
├─── release/1.2.0
│       ↳ main + develop へマージ
│
├─── feature/user-auth
│       ↳ develop へマージ
│
└─── bugfix/fix-profile-issue
        ↳ develop へマージ