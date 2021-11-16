# Big_data_Siheung_project

빅데이터 시흥시 연계 프로젝트
버스의 포화도 계산과 버스 탄력배차시간 제안

![image](https://user-images.githubusercontent.com/25499386/141924796-2525be53-d28c-463b-b0af-accb7cb0a33d.png)


<h2>분석 목적</h2>

![image](https://user-images.githubusercontent.com/25499386/141924675-5c1f1bc6-ed18-40c8-98f8-bff36486b438.png)

![image](https://user-images.githubusercontent.com/25499386/141924726-048db847-2157-48ee-9db6-427530008109.png)

![image](https://user-images.githubusercontent.com/25499386/141924743-3722bf9e-d5e6-4d1d-89a7-67481bcdc792.png)

<h2>분석 내용</h2>

<br>
<h3>1.경기도 버스포털에서 시흥시 경유 및 내부운행 21년도 버스 데이터들을 수집 및 정제과정을 거침</h3>

<h3>2.각 버스별 평균배차시간 계산 및 버스 노선당 시간대별 포화도 계산</h3>

<p>포화도 계산식 :
  
  ![image](https://user-images.githubusercontent.com/25499386/141925244-3fec0813-1d9d-49b1-94bf-982d1ef3834d.png)
  

![image](https://user-images.githubusercontent.com/25499386/141925328-45c2ff0a-0a4f-4620-a515-0e589eb220f0.png)

  ※단, 여기서 버스적정 탑승인원은 운전자를 제외한 40명
</p>
<h3>3.각 버스별 포화도순으로 정렬한 뒤, 적정배차시간 계산 (포화도 100기준으로)</h3>
<p>(단, 모든 차량은 증차가 될 경우 동일노선 다른 시간대에서 감차가 동일하게 이루어 져야함!)</p>

<h2>분석 결과</h2>
<br>

![image](https://user-images.githubusercontent.com/25499386/141925836-6b9d59af-a485-4f54-bcc4-b7c4455e3168.png)

![image](https://user-images.githubusercontent.com/25499386/141925882-a78d56bf-654e-4e5a-8d45-fa3e6901ebe8.png)



<h2>분석 결과 설명</h2>
<br>

![image](https://user-images.githubusercontent.com/25499386/141925980-1ca142f7-c6d3-4506-97ca-059410efc506.png)

![image](https://user-images.githubusercontent.com/25499386/141926003-dda2635d-8f9a-46e9-945a-f2fc557f732f.png)

![image](https://user-images.githubusercontent.com/25499386/141926021-5492ac1e-5506-474a-b89f-bac8d2e21298.png)

![image](https://user-images.githubusercontent.com/25499386/141926032-569e4a15-9f55-41e4-bca0-4414a19b7b5e.png)

![image](https://user-images.githubusercontent.com/25499386/141926056-b3462487-7d0f-4f7d-9040-093ae779eb5d.png)




