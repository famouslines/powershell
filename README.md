# 이것만 기억하자
1. 동사 + 명사로 구성된다. 
```powershell
> Get-Help
```
2. 동사 중 Get은 기본 동사라서 생략 가능하다
```powershell
> Help
```
3. Get-Help와 Get-Command만 기억하자
```powershell
> Get-Help Get-Command
```
4. Get-Command에서는 1의 내용을 기억하자. 즉, 동사와 명사를 조합하면 의도하는 명령어를 찾을 수 있다.
아래는 디스크 관련된 정보를 얻어오는 명령어가 있는 지 확인해 보는 예시이다. 
```powershell
> Get-Command -Noun Disk* -Verb Get*
```
5. Get-Disk를 알아냈다면 사용법을 확인하자
```powershell
> Get-Help Get-Disk -full 
```
