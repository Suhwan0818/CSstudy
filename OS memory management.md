# 메모리란?  
메인 메모리, RAM을 뜻합니다. 프로그램 실행 시 필요한 주소, 정보들을 저장하고 가져다 사용할 수 있게 만드는 공간. 즉, 작업을 위해 사용되는 공간입니다.  

### 메모리 관리를 왜?  
프로세스는 각각의 메모리를 지니고 있습니다. 아래 그림은 위키백과에서 가져온 이미지 입니다.  
![process-memory](/img/process-memory.png)  
메모리가 단순 존재하는 것만이 아닌 정말 많은 데이터를 들고 있다는 사실을 확인할 수 있습니다. **이 데이터를 누가 관리하고? 누가 접근이 가능하지?** 라는 의문이 생깁니다. 해당 의문을 답해주는 것이 OS가 하는 일입니다.  

메모리 관리에 잇어서 **운영체제의 역할**의 역할은 **실행 파일이 로더에 의해 메모리에 올라오고 운영체제는 이 실행 파일을 메모리 어느 부분에 올릴지를 결정**합니다. 혹은 **가상머신을 이용해 간접적으로 접근**합니다.  

### 가상 메모리란?  
실제 자신이 가지고 있는 물리적인 메모리(RAM)보다 큰 주소 공간을 프로세스에게 빌려주는 기술입니다.  
가상 공간에 대한 설명을 처음 봤을때 떠오른 것은 은행입니다. 만약 