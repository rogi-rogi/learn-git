# Learn Git

## Area

### Working Directory

```.git```폴더를 제외한 나머지 공간.

작업 내용을 반영하고 싶으면 ```Staging Area```에 ```add```해야 한다.

```bash
git add 파일명
```


<br>

### Staging Area

```Working Directory```에서 ```add```된 변경 데이터에 대한 이력을 기록하기 위해 모아둔 공간.

```commit```을 하면```.git```폴더 내 ```index```에 기록된다.

<br>

## Git Life Cycle

### Untracked

Git이 관리하지 않는 파일. ```add```로 ```Staged```상태로 변경 가능

### Unmodified

```Stated```상태에서 ```commit```이후의 상태, 변경시 ```Modified```상태가 된다.


### Modified

Git에서 관리되는 파일이 변경된 상태. ```add```로 ```Stated```상태로 변경해야 한다.

### Staged

수정된 파일을 ```Repository```에 반영할 준비가 된 상태

<br>

## command


<br>


## Reference

[2.2 Git Basics - Recording Changes to the Repository](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository)