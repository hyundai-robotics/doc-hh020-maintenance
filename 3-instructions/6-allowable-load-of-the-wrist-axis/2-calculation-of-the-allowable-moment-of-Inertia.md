﻿# 3.6.2. 허용 관성 모멘트 산정

표 [3-3]~[3-5]를 참고하여 부하가 허용조건을 초과하지 않도록 사용하여 주십시오.

*	Step 1

    각 손목축 중심에서 부하의 관성 모멘트 값을 계산 (J<sub>a4</sub>, J<sub>a5</sub>, J<sub>a6</sub>)

    J<sub>a4</sub> - R2축 회전 중심에서의 관성 모멘트

    J<sub>a5</sub> - B축 회전 중심에서의 관성 모멘트

    J<sub>a6</sub> - R1축 회전중심에서의 관성 모멘트

*	Step 2

    허용 관성 모멘트 표를 기준으로 관성 모멘트 값이 제한치 이하인지 확인


![](../../_assets/작은주의표시.png) <b>허용 관성모멘트</b>

표 3-3 허용 관성 모멘트
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-zegx{background-color:#f8f8be;color:#000000; font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-zegx" rowspan="2">로봇모델</th>
    <th class="tg-zegx" colspan="3">허용 관성 모멘트</th>
  </tr>
  <tr>
    <th class="tg-zegx">R2축 회전</th>
    <th class="tg-zegx">B축 회전</th>
    <th class="tg-zegx">R1축 회전</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">HH020</td>
    <td class="tg-nrix" colspan="2">0.88kgm²(0.088kgfms²)</td>
    <td class="tg-nrix">0.25kgm²(0.025kgfms²)</td>
  </tr>
  <tr>
    <td class="tg-nrix">HH020T</td>
    <td class="tg-nrix">-</td>
    <td class="tg-nrix">0.88kgm²(0.088kgfms²)</td>
    <td class="tg-nrix">0.25kgm²(0.025kgfms²)</td>
  </tr>
 <tr>
    <td class="tg-nrix">HH010L</td>
    <td class="tg-nrix" colspan="2">0.63kgm²(0.063kgfms²)</td>
    <td class="tg-nrix">0.15kgm²(0.015kgfms²)</td>
  </tr>
</tbody>
</table>