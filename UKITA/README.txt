UKITA란 우크라이나와 러시아 전쟁이 시작되면서 자원봉사 해커들 즉 어나니머스들을 모집하기 시작했다.
해킹 지식이 없어도 된다. 해킹 경력이 없어도 된다. 왜냐하면 우리가 튜토리얼 지침을 보내줄거니까.
이때 생긴 프로그램이 UKITA (자동화 DDOS 프로그램이다.)

사명:
IT ARMY는 침략자 경제를 마비시키고, 중요한 재정, 인프라 및 정부 서비스를 차단하고, 주요 납세자를 지치게 함으로써 우크라이나가 승리하도록 돕는 것을 목표로 합니다. 또한 적대적인 미디어 선전을 중단하고 전쟁에 대한 진실을 퍼뜨립니다. 우리는 침략자 국가의 모든 거주자가 자국의 침략을 느끼고 지치기를 바랍니다.

우크라이나에 영광을!

프로그램은

UKITA, MHDDOS, DISTRESS,  db1000nx100 가 있다.

URL은 공개하지 않겠다.
각 github에 포함되어 있지만 이 코드들을 수정하여 악용 할 가능성이 있기 때문이다.

!!우크라이나 IT군과 함께 침략국의 경제를 파괴하십시오!!

1. MHDDOS
- VPN 필요 없음 (조건부) - 자동으로 다운로드하고 작동하는 프록시를 선택하고 현재 사용 중인 설정을 정기적으로 변경합니다.
- 자동 로드 밸런싱으로 여러 타겟을 동시에 공격
- 다양한 공격 방법을 사용하고 자동으로 전환합니다.
- 명확한 매개변수를 갖춘 사용자 친화적 인터페이스

VPN
VPN을 통한 공격에는 몇 가지 미묘한 차이점이 있습니다.

VPN이 필요한지 어떻게 알 수 있나요?

15분 동안 VPN 없이 공격하고 인터넷 연결이 안정적이며 스크립트가 잘 작동하는 경우(전체 트래픽 25Mbit/s 이상 생성) 아무것도 변경할 필요가 없습니다.

VPN 없이 공격하고 웹 브라우징/인터넷 연결 끊김 및/또는 스크립트의 총 트래픽(15Mbit/s 미만) 문제가 있는 경우 VPN에 연결하여 더 잘 작동하는지 확인해야 할 수 있습니다(동일한 총 트래픽 필드)

설정
모든 매개변수는 혼합될 수 있으며, 대상 목록 앞과 뒤에 배치될 수 있습니다. 최신 매개변수 목록은 여기에서 찾을 수 있습니다 .

CPU 코어가 3개 이상이고 네트워크 대역폭이 100Mb/s 이상인 경우 매개변수를 추가하여 mhddos_proxy의 여러 사본을 실행할 수 있습니다.--copies auto

2. DISTRESS

- 기본적으로 가능한 모든 국가의 프록시를 사용합니다.
- Tor 종료 노드에 대한 내장 지원( --use-tor플래그 참조)
- CPU 사용량 낮음
- 다양한 플랫폼을 지원합니다
- ITArmy **에서 타겟 자동 업데이트
- 진보된 DDOS 방법

3. db1000nX100 
db1000nX100은 각각 별도의 db1000n 또는 distress 애플리케이션을 실행하는 여러 병렬 VPN 연결을 자동으로 설정합니다.
IP 주소는 다른 VPN 서버에 다시 연결되기 때문에 15분마다 변경됩니다.
이를 통해 공격이 시작되는 IP 주소가 지속적으로 변경됩니다.

동시 VPN 연결 수	100개 이상 *

* 최대 연결 수는 사용자가 할당한 컴퓨터 자원을 기준으로 자동으로 계산됩니다. 예를 들어 CPU 코어 6개와 RAM 16GB를 사용하는 경우 100개 이상의 서로 다른 IP 주소에서 동시에 공격이 발생합니다.

15분마다 IP 주소 자동 변경 기능

격리된 컨테이너
(보안 강화, 바이러스 방지) 기능

컴퓨터에 VPN 프로그램을 설치해야 할 필요성	필요 없음

앱을 사용하기 전에 VPN을 수동으로 활성화해야 합니다.	필요 없음

연결된 VPN이 네트워크 속도에 미치는 영향	없음 *

* VPN 연결은 VBox/Docker 컨테이너 내부에서 발생합니다.

프로그램의 일회성 구성 필요성	* * 약 10~15분 정도 소요됩니다 .

이 도구들은 텔레그램을 통해서 타겟에 대한 영향과 현재 상황등을 확인 가능하다.

업로드 날짜 기준 ddos 1위는 서버 36개로 846,66테라바이트의 ddos를 날렸다.