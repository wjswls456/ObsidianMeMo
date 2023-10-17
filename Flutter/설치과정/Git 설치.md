사이트 주소 :  https://git-scm.com/download/


![[Pasted image 20231017122544.png]]

📌 해당 운영체제에 맞게 다운로드 진행 하시면 됩니다.


📢 약관을 읽고 "Next"를 눌러줍니다.


![[Pasted image 20231017122616.png]]


📢**Git이 설치될 경로를 지정하고 "Next"를 눌러줍니다.

![[Pasted image 20231017122706.png]]


📢 설치할 구성요소를 지정하고 "Next"를 눌러줍니다.
**(각 구성요소 별 설명은 바로 아래 있습니다.)** **(저는 화면과 같이 진행했습니다.)**

![[Pasted image 20231017122718.png]]

📌 **Additional icons**  
- On the Desktop : 바탕화면에 바로가기 생성  
📌 ✅**Windows Explorer integration**  
- ✅Git Bash Here : 폴더 오른쪽 클릭 메뉴에 Git Bash Here(연결 기능) 추가  
- ✅Git GUI Here : 폴더 오른쪽 클릭 메뉴에 Git GUI Here(연결 기능) 추가  
📌 ✅**Git LFS (Large File Support)**  
- 대용량 파일 지원  
📌 ✅**Associate .git* configuration files with the defalut text editor**  
- 기본 텍스트 에디터에 git 구성(.git 확장자) 연결  
📌 ✅**Associate .sh files to be run with Bash**  
- Bash에 .sh 확장자 파일 연결  
📌 **Check daily for git for Windows updates**  
- 매일 새로운 업데이트 확인  
📌 **(NEW!) Add a Git Bash Profile to Windows Terminal**  
- 윈도우 기본 터미널에 Git Bash 프로파일 추가


**📢시작 메뉴 바로가기 및 폴더 경로를 지정하고 "Next"를 눌러줍니다.
(만들기를 원하지 않는다면 아래 "Dont' create a Start Menu folder"에 체크합니다.)

![[Pasted image 20231017122741.png]]


**📢Git의 기본 편집기를 선택하고 "***Next****"를 눌러줍니다. 저는 Vim을 거의 사용하지 않아 익숙지 않은 관계로 "Visual Studio Code"를 선택했습니다. 추천사항은 없고 각자 편하신 편집기를 선택하시면 됩니다.

![[Pasted image 20231017122746.png]]


📢새 Repository를 생성할 때 initial branch 이름을 지정하는 방법을 선택 후 "Next"를 눌러줍니다.


![[Pasted image 20231017122750.png]]


📌 ✅**Let Git decide** : 새로운 Repository의 initial branch에 기본 분기 이름("master")을 사용합니다.  
📌 **Override the default branch name for new repositories** : 새로운 Repository의 initial branch에 사용자 지정 분기 이름을 사용합니다. 이미 팀에서 관용적으로 쓰는 명칭이 있을 때 사용하면 됩니다.

📢Git커맨드를 사용하기 위한 환경변수를 설정하고 "**Next"를 눌러줍니다.
**(저는 화면과 같이 그대로 진행하였습니다.)**


![[Pasted image 20231017122755.png]]

📌**Use Git from Git Bash only** : Git Bash에서만 Git 명령어를 수행할 수 있습니다.  

📌✅**Git from the command line and also from 3rd-party software** : Git을 환경변수(PATH)에 추가하여 윈도우 기본 명령 프롬프트(CMD) 등에서도 Git 명령어를 수행할 수 있습니다.

📌**Use Git and optional Unix tools from the Command Prompt** : Git과 Unix 도구 모두 환경변수(PATH)에 추가합니다. 이 경우 몇 가지 Windows 기본 도구가 새롭게 재정의 됩니다. 이러한 위험을 충분히 숙지하고 있는 경우에만 이 옵션을 사용하기를 권장합니다.



📢SSH 실행 도구를 선택하고 "Next"를 눌러줍니다.


![[Pasted image 20231017122806.png]]


📌✅**Use bundled OpenSSH** : Git에서 기본으로 제공되는 OpenSSH를 사용합니다.  
📌**Use external OpenSSH** : 외부 OpenSSH를 사용합니다. 이 경우 Git에서 기본 제공하는 OpenSSH는 따로 설치되지 않으며 PATH에 명시된 OpenSSH를 사용합니다.



📢HTTP 연결 옵션을 선택하고 "Next"를 눌러줍니다.
![[Pasted image 20231017122811.png]]

📌✅**Use the OpenSSL library** : OpenSSL 라이브러리를 사용합니다. ca-bundle.crt 파일로 검증합니다.  
📌**Use the native Windows Secure Channel library** : Windows 인증서 저장소를 사용하여 검증합니다. 이 옵션은 Active Directory 도메인 서비스를 통한 회사의 내부 Root CA 인증서를 사용할 수 있습니다.


📢Git 저장소에 체크인/아웃할 때의 줄 바꿈 방법을 선택하고 "Next"를 눌러줍니다.
❗ **이 옵션은 무엇을 의미하나요?**  
윈도우와 유닉스의 개행(줄 바꿈) 표기가 서로 다릅니다. (윈도우: \r\n 유닉스: \n)  
따라서 여러 운영체제에서 작업할 경우, 개행 표기가 달라져 수정 사항이 없음에도 수정된 것으로 인식할 가능성이 있습니다. 이 문제를 해결하기 위해 설정하는 옵션입니다.

![[Pasted image 20231017122824.png]]


📌✅**Checkout Windows-style, commit Unix-style line endings** : 체크아웃은 윈도우 스타일, 커밋은 유닉스 스타일로 자동 변경되도록 설정합니다.  
📌**Checkout as-is, commit Unix-style line endings** : 체크아웃은 변경 없이, 커밋은 유닉스 스타일로 설정합니다.  
📌**Checkout as-is, commit as-is** : 체크아웃, 커밋 모두 스타일 변경 없이 진행합니다.



📢Git Bash 터미널 에뮬레이터를 선택하고 "Next"를 눌러줍니다.

![[Pasted image 20231017122829.png]]

📌✅**Use MinTTY (the default terminal of MSYS2)** : Git Bash 기본 터미널 에뮬레이터(MinTTY)를 사용합니다.  
📌**Use Windows' default console window** : 윈도우 기본 콘솔(cmd)을 사용합니다.


📢'git pull' 명령어에 수행될 작업을 선택하고 "Next"를 눌러줍니다.


![[Pasted image 20231017122838.png]]

📌✅**Default (fase-forward or merge)** : 'git pull'의 수행 동작을 기본으로 설정합니다.  
📌**Rebase** : 'git pull'의 수행 동작으로 현재 분기를 불러온 분기에 재배치합니다.  
📌**Only ever fase-forward** : 'git pull'의 수행 동작으로 불러온 분기로 빠르게 넘어갑니다. 명령어 수행에 실패할 가능성이 있습니다.

📢자격 증명 도우미를 선택하고 "Next"를 눌러줍니다.

![[Pasted image 20231017122846.png]]

📌✅**Git Credential Manager Core** : Git의 자격 증명 도우미를 사용합니다.  
📌**None** : 자격 증명 도우미를 사용하지 않습니다.

📢기타 옵션을 선택하고 "Next"를 눌러줍니다.

![[Pasted image 20231017122852.png]]



![[Pasted image 20231017122859.png]]