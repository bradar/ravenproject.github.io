---
layout: page-w-banner
title: 렛저
bannerTitle: 렛저 나노 사용법
bannerImage: /assets/img/pages/wallet/wallet-banner.jpg
permalink: /ledger/
---

<div class="wrapper mt-16 pb-20">
  <h2>렛저 나노 S 및 나노 X 사용법</h2>

  <p>렛저 나노 S 및 나노 X는 하드웨어 지갑입니다. 하드웨어 지갑은 코인 사용을 위한 개인키를 저장하는 매우 안전한 방법입니다. 레이븐코인 앱을 설치하면 레이븐코인을 관리할 수 있습니다. 그러나 현재로서는 레이븐코인 자산 관리를 지원하지 않습니다. 해당 기능을 사용할 수 있게 되면 이 문서는 레이븐코인 자산 관리 방법에 대한 지침도 포함될 예정입니다.</p>

  <br>
  <h3>시작 전</h3>

  <ul>
    <li>다운로드 및 설치 <a href="https://support.ledger.com/hc/en-us/articles/360006395553">Ledger Live</a>.</li>
    <li><a href="https://support.ledger.com/hc/en-us/articles/360006395233">렛저 설치</a></li>
    <li><a href="https://support.ledger.com/hc/en-us/articles/360002731113-Update-Ledger-Nano-S-firmware">최신 버전의 렛저 펌웨어 업데이트</a></li>
    <li>최신 버전의<a href="https://support.ledger.com/hc/en-us/articles/115005195945">비트코인 앱 설치</a></li>
  </ul>

  <br>
  <h3>렛저에 레이븐코인 앱 설치</h3>

  <ul>
    <li>렛저 연결 및 잠금 해지</li>
    <li>렛저 라이브 열기, 그리고  메뉴에서 매니저 선택</li>
    <li>렛저에서 매니저 허용</li>
    <li>앱에서 레이븐코인 앱 찾기</li>
    <li>레이븐코인 앱을 위한 설치 버튼 클릭</li>
    <li>설치창이 나타납니다. "앱 필요" 라는 대화 상자가 표시되면 먼저 최신 비트코인 앱을 설치하거나 업그레이드 해야함을 의미합니다.</li>
    <li>설치 확인 후 설치 창 및 렛저 라이브 닫기</li>
  </ul>

  <br>
  <h3>일렉트럼 레이븐코인 지갑 설치</h3>

  <p><a href="https://github.com/Electrum-RVN-SIG/electrum-ravencoin">일렉트럼 지갑</a> 지갑 다운로드
    사전 빌드된 바이너리의 경우 다음을 확인해주시길 바랍니다. <a href="https://github.com/Electrum-RVN-SIG/electrum-ravencoin/releases">릴리즈 탭</a>
  </p>

  <p>일렉트럼 레이븐코인 지갑을 처음 설정할 때 다음 단계를 따르십시오:</p>

  <ul>
    <li>계속하기 전에 원장 장치를 컴퓨터에 연결하고, 잠금 해지 후, 레이븐코인 앱에 들어가야 합니다.</li>
    <li>렛저 라이브가 닫혀있는지 확인 후, 일렉트럼 레이븐코인을 엽니다.</li>
    <li>첫번째 화면에는 컴퓨터에 생성될 지갑 파일의 이름이 있는 텍스트 상자가 표시됩니다. default_wallet이라는 이름을 갖게 됩니다. 이 이름을 바꾸거나 그대로 둔 후, '다음'을 클릭합니다.</li>
    <li>두번째 화면에는 표준 지갑, 다중 서명 지갑 및 레이븐코인 주소 또는 개인 키 가져오기의 세가지 옵션이 표시됩니다. 표준 지갑 옵션을 선택하고, '다음'을 클릭합니다.</li>
    <li>세번째 화면에는 새 시드 만들기, 기존 시드 존재, 마스터 키 사용 및 하드웨어 장치 사용의 총 4가지 옵션이 표시됩니다. 하드웨어 장치 사용을 선택하고 '다음'을 클릭합니다.</li>
    <li>프로그램은 하드웨어 장치를 사용할 수 있는지 검사합니다. 그렇다면 이름 없는 원장 [원장, 초기화됨]을 선택하는 옵션이 표시되어야 합니다. '다음'을 클릭합니다.</li>
    <li>지갑에서 주소 유형을 선택하라는 메시지가 표시됩니다. 옵션은 하나뿐이므로 그대로 둘 수 있습니다. 아래 텍스트 상자에 올바른 파생 경로가 표시됩니다. '다음'을 클릭합니다.</li>
    <li>다음 화면은 지갑 파일을 암호화 여부를 묻습니다. 이 파일에는 애플리케이션을 사용하여 관리하는 주소를 보기 위한 메타데이터와 마스터 공개 키가 포함되어 있습니다. 개인 키는 응용 프로그램이나 컴퓨터와 공유되지 않으며 장치에 남아 있습니다. 지갑 파일을 암호화하는 경우 지갑을 사용하려면 장치를 연결하고 레이븐코인 앱을 열어야 합니다. 지갑 파일을 암호화하지 않으면 장치 없이 열 수 있지만, 코인을 보내거나 수신 주소를 확인할 때 여전히 장치가 필요합니다.</li>
    <li>이제 지갑이 설정되었습니다.</li>
  </ul>

  <p>초기 설정 후 일렉트럼 레이븐코인 지갑을 사용하는 경우:</p>

  <ul>
    <li>지갑 파일을 암호화한 경우, 렛저 장치를 연결하고 레이븐코인 앱을 열어야 합니다.</li>
    <li>일렉트럼 레이븐코인 지갑에서 열려는 지갑 파일을 선택하고 '다음'을 클릭합니다.</li>
    <li>지갑이 열리고 RVN을 보내고 받을 수 있습니다.</li>
  </ul>

  <br>
  <h3>일렉트럼 레이븐코인 지갑 사용법</h3>


  <p> 지갑이 열리면 상단에 파일, 지갑, 보기, 도구 및 도움말의 5가지 옵션이 표시됩니다. 또한 기록, 보내기 및 받기라는 레이블이 붙은 3개의 탭이 표시됩니다. 지갑이 열리면 지갑 애플리케이션의 왼쪽 하단에 계정 잔액이 표시됩니다. 어떤 탭을 열어도 볼 수 있습니다. 기록 탭에는 계정을 사용한 거래 기록이 표시되고, 보내기 탭에서는 트랜잭션을 생성하고 레이븐코인 블록체인에 브로드캐스트할 수 있으며, 수신 탭에서는 수신 RVN의 수신 주소를 선택하고 확인할 수 있습니다.</p>

  <br>
  <h3>레이븐코인을 받기 위한 일렉트럼 레이븐코인 지갑 사용법</h3>

  <ul>
    <li>수신 탭을 클릭합니다.</li>
    <li>지갑은 "수신 주소"라고 표시된 텍스트 상자에 표시될 수신 주소를 자동으로 선택합니다. 원하는 경우 이전에 사용한 주소를 사용할 수 있지만 최적의 개인 정보를 제공하지 않습니다.</li>
    <li>장치의 수신 주소를 확인하려면 "수신 주소" 텍스트 상자의 오른쪽에 있는 눈 모양 아이콘을 클릭하십시오.</li>
    <li>"주소 표시"라는 작은 텍스트 상자가 나타납니다.</li>
    <li>오른쪽 버튼을 몇 번 클릭하여 전체 주소를 확인한 다음 주소 승인 또는 거부를 선택하여 렛저 장치의 수신 주소를 확인하십시오.</li>
    <li>수신할 RVN의 요청 금액을 입력하고 저장을 클릭합니다.</li>
    <li>RVN을 보낼 사람에게 수신 주소를 제공하십시오.</li>
  </ul>

  <br>
  <h3>레이븐코인 전송을 위한 일렉트럼 레이븐코인 지갑 사용법</h3>

  <ul>
    <li>보내기 탭을 클릭합니다.</li>
    <li>받는 사람 주소를 "지불 대상" 텍스트 상자에 붙여넣습니다.</li>
    <li>자신의 기록에 대한 선택적 설명을 입력합니다.</li>
    <li>"금액"란에 보내고자 하는 RVN의 양을 입력하십시오.</li>
    <li>렛저 장치로 보내기 전에 거래 내역을 미리 보려면 미리보기 버튼을 클릭하십시오.</li>
    <li>보내기 버튼을 클릭합니다.</li>
    <li>보낼 금액과 거래에 대한 채굴 수수료를 알려주는 작은 창이 나타납니다.</li>
    <li>계속하려면 예를 클릭합니다.</li>
    <li>기기에서 거래 세부정보를 검토하고 확인합니다. 세부 정보가 표시될 때까지 몇 초 정도 기다려야 할 수 있습니다.</li>
    <li>오른쪽 버튼을 몇 번 클릭하여 금액과 수취인 주소를 확인한 후 거래 승인 또는 거부를 선택합니다.</li>
  </ul>

  <br>
  <h3>지원</h3>

  <p>Ravencoin과 함께 Ledger 장치를 사용하는 데 도움이 필요한 경우 다음을 통해 커뮤니티에 연락할 수 있습니다;<a href="https://t.me/RavencoinKorea">텔레그램</a> and <a href="https://discord.gg/VuubYncHz4">디스코드</a>.</p>
</div>
