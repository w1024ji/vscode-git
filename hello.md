hi
im w1024ji


# restore는 아예 사라지는 건가? 복구..이니까
- use "git restore --staged <file>... " to unstage

## remote랑 clone은 뭐가 다른거지

# fetch + merge = pull
- pull: 원격 리포지터리에서 최신 커밋들을 받아서 현재 로컬 브랜치와 '자동'으로 merge
- fetch: 원격 리포지터리에서 최신 커밋들을 이름없는 임시 브랜치로 받고, merge을 진행하지 않음
    즉, 개발자가 수동으로 merge 해줘야 한다. 
    이때 브랜치는 FETCH_HEAD의 이름으로 checkout이 가능함.
