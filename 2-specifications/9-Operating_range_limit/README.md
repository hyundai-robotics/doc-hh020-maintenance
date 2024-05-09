﻿# 2.9. 동작 범위 제한

로봇 설치 시, 전체 동작범위 안에서 특정범위로 제한할 수 있습니다. 

다음과 같은 환경에서 동작범위의 제한은 유용합니다.

*	로봇 동작 시 동작영역을 제한하자고 할 때
*   주변기기와 충돌이 발생할 수 있을 때
*   응용케이블이나 호스의 길이가 제한적일 때


로봇이 동작영역을 벗어나지 않게 하는 방법에는 3가지가 있습니다. 즉,

*	소프트웨어 리미트(전축 적용)
*	리미트 스위치(1~3축: 옵션)
*	기계적 스토퍼(Stopper)(1~3축)


<img src="../../_assets/작은주의표시.png"><b>[주의]</b><br>
기계적 스톱퍼는 물리적인 장치입니다. 로봇은 기계적 스톱퍼를 넘어서는 안됩니다. 1~3축의 기계적 스톱퍼는 고정되어있습니다. 4~6축은 소프트웨어 리밋 만 적용되어 있습니다.

기계적 스톱퍼는 한 번 충돌하면 변형되며, 강도를 보장할 수 없습니다. 따라서, 반드시 교체해주십시오.